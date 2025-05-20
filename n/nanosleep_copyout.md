# Function: <code>nanosleep_copyout</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fff20)
Location: kernel/time/hrtimer.c:1443
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff810fff20-ffffffff810fff69: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110ad10)
Location: kernel/time/hrtimer.c:1448
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff8110ad10-ffffffff8110ad59: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116700)
Location: kernel/time/hrtimer.c:1659
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff81116700-ffffffff81116749: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121d40)
Location: kernel/time/hrtimer.c:1649
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff81121d40-ffffffff81121d89: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112c690)
Location: kernel/time/hrtimer.c:1649
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff8112c690-ffffffff8112c6d9: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811386b0)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff811386b0-ffffffff811386f9: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811474c0)
Location: kernel/time/hrtimer.c:1851
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811474c0-ffffffff81147509: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811439d0)
Location: kernel/time/hrtimer.c:1868
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811439d0-ffffffff81143a19: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144b80)
Location: kernel/time/hrtimer.c:1868
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81144b80-ffffffff81144bc6: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811683d0)
Location: kernel/time/hrtimer.c:2016
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811683d0-ffffffff81168416: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119bdf0)
Location: kernel/time/hrtimer.c:2016
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff8119bdf0-ffffffff8119be4a: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811da750)
Location: kernel/time/hrtimer.c:2016
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811da750-ffffffff811da7aa: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811eec80)
Location: kernel/time/hrtimer.c:2019
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811eec80-ffffffff811eecda: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81204e00)
Location: kernel/time/hrtimer.c:2020
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81204e00-ffffffff81204e5a: nanosleep_copyout (STB_GLOBAL)
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
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a2328)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffff8000101a2328-ffff8000101a239c: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ec044)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
c03ec044-c03ec0ac: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0000000002037f0)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
c0000000002037f0-c00000000020387c: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f486)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffe00012f486-ffffffe00012f4cc: nanosleep_copyout (STB_GLOBAL)
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
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130e60)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff81130e60-ffffffff81130ea9: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811238d0)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff811238d0-ffffffff81123919: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112eb80)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff8112eb80-ffffffff8112ebc9: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nanosleep_copyout(struct restart_block *restart, struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113b580)
Location: kernel/time/hrtimer.c:1846
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
**Symbols:**

```
ffffffff8113b580-ffffffff8113b5c9: nanosleep_copyout (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
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
