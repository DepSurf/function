# Function: <code>set_process_cpu_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, cputime_t *newval, cputime_t *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f4040)
Location: kernel/time/posix-cpu-timers.c:1249
Inline: False
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff810f4040-ffffffff810f417b: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, cputime_t *newval, cputime_t *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fb1c0)
Location: kernel/time/posix-cpu-timers.c:1220
Inline: True
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
**Symbols:**

```
ffffffff810fb1c0-ffffffff810fb2f8: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, cputime_t *newval, cputime_t *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81108b40)
Location: kernel/time/posix-cpu-timers.c:1216
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81108b40-ffffffff81108c78: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110ad20)
Location: kernel/time/posix-cpu-timers.c:1187
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff8110ad20-ffffffff8110ae37: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115ed0)
Location: kernel/time/posix-cpu-timers.c:1186
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81115ed0-ffffffff81115fe7: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811226f0)
Location: kernel/time/posix-cpu-timers.c:1202
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811226f0-ffffffff81122811: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112ddd0)
Location: kernel/time/posix-cpu-timers.c:1200
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff8112ddd0-ffffffff8112def1: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clock_idx, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811387f0)
Location: kernel/time/posix-cpu-timers.c:1199
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811387f0-ffffffff81138915: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81144550)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81144550-ffffffff811445e7: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153a94)
Location: kernel/time/posix-cpu-timers.c:1157
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81153eb0-ffffffff81153f4a: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114ff04)
Location: kernel/time/posix-cpu-timers.c:1323
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81150210-ffffffff811502aa: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81151334)
Location: kernel/time/posix-cpu-timers.c:1323
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81151640-ffffffff811516d7: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175704)
Location: kernel/time/posix-cpu-timers.c:1396
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff81175a40-ffffffff81175b05: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa651)
Location: kernel/time/posix-cpu-timers.c:1403
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811aaa10-ffffffff811aaaf5: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea6f1)
Location: kernel/time/posix-cpu-timers.c:1403
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811eab10-ffffffff811eabf5: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fee21)
Location: kernel/time/posix-cpu-timers.c:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811ff260-ffffffff811ff345: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81215175)
Location: kernel/time/posix-cpu-timers.c:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff821b5d06-ffffffff821b5d1a: set_process_cpu_timer.cold (STB_LOCAL)
ffffffff81215620-ffffffff81215747: set_process_cpu_timer (STB_GLOBAL)
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
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101aea90)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffff8000101aea90-ffff8000101aeb4c: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f9b9c)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
c03f9b9c-c03f9cac: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000213090)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
c000000000213090-c0000000002131a0: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013847a)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffe00013847a-ffffffe00013852a: set_process_cpu_timer (STB_GLOBAL)
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
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113cd00)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff8113cd00-ffffffff8113cd97: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f820)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff8112f820-ffffffff8112f8e1: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113aa20)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff8113aa20-ffffffff8113aab7: set_process_cpu_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_process_cpu_timer(struct task_struct *tsk, unsigned int clkid, u64 *newval, u64 *oldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811474e0)
Location: kernel/time/posix-cpu-timers.c:1178
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff811474e0-ffffffff81147577: set_process_cpu_timer (STB_GLOBAL)
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
<code>cputime_t *newval</code> ➡️ <code>u64 *newval</code>
</li>
<li>
<b>Param type changed. </b>
<code>cputime_t *oldval</code> ➡️ <code>u64 *oldval</code>
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
<code>unsigned int clkid</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int clock_idx</code>
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
