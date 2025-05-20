# Function: <code>do_cpu_nanosleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct itimerspec *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3440)
Location: kernel/time/posix-cpu-timers.c:1295
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff810f3440-ffffffff810f3669: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct itimerspec *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fa550)
Location: kernel/time/posix-cpu-timers.c:1266
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff810fa550-ffffffff810fa78a: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct itimerspec *it);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107ed0)
Location: kernel/time/posix-cpu-timers.c:1262
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff81107ed0-ffffffff81108101: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110a130)
Location: kernel/time/posix-cpu-timers.c:1233
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff8110a130-ffffffff8110a383: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811152f0)
Location: kernel/time/posix-cpu-timers.c:1232
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff811152f0-ffffffff8111554e: do_cpu_nanosleep (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff81121a90)
Location: kernel/time/posix-cpu-timers.c:1249
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff81121a90-ffffffff81121ce5: do_cpu_nanosleep.isra.19 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff8112d1b0)
Location: kernel/time/posix-cpu-timers.c:1247
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff8112d1b0-ffffffff8112d405: do_cpu_nanosleep.isra.19 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff81137c00)
Location: kernel/time/posix-cpu-timers.c:1246
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff81137c00-ffffffff81137e0d: do_cpu_nanosleep.isra.0 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff81143c40)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff81143c40-ffffffff81143e72: do_cpu_nanosleep.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153680)
Location: kernel/time/posix-cpu-timers.c:1198
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff81153680-ffffffff8115388c: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114faa0)
Location: kernel/time/posix-cpu-timers.c:1364
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff8114faa0-ffffffff8114fcc7: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150ee0)
Location: kernel/time/posix-cpu-timers.c:1364
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff81150ee0-ffffffff81151108: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811752b0)
Location: kernel/time/posix-cpu-timers.c:1436
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff811752b0-ffffffff811754d7: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a9bd0)
Location: kernel/time/posix-cpu-timers.c:1443
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff811a9bd0-ffffffff811a9e00: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e9b30)
Location: kernel/time/posix-cpu-timers.c:1443
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff811e9b30-ffffffff811e9d60: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fe220)
Location: kernel/time/posix-cpu-timers.c:1501
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff811fe220-ffffffff811fe465: do_cpu_nanosleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812145b0)
Location: kernel/time/posix-cpu-timers.c:1501
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
```
**Symbols:**

```
ffffffff812145b0-ffffffff812147f5: do_cpu_nanosleep (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffff8000101ae098)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffff8000101ae098-ffff8000101ae3b0: do_cpu_nanosleep.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f9008)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
c03f9008-c03f92a4: do_cpu_nanosleep (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (c000000000212500)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
c000000000212500-c0000000002128cc: do_cpu_nanosleep.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_cpu_nanosleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe000137c54)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffe000137c54-ffffffe000137f0c: do_cpu_nanosleep (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff8113c3f0)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff8113c3f0-ffffffff8113c622: do_cpu_nanosleep.isra.0 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff8112eeb0)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff8112eeb0-ffffffff8112f0ca: do_cpu_nanosleep.isra.0 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff8113a110)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff8113a110-ffffffff8113a342: do_cpu_nanosleep.isra.0 (STB_LOCAL)
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
In kernel/time/posix-cpu-timers.c (ffffffff81146b30)
Location: kernel/time/posix-cpu-timers.c:1219
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
```
**Symbols:**

```
ffffffff81146b30-ffffffff81146d3a: do_cpu_nanosleep.isra.0 (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct itimerspec *it</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct timespec *rqtp</code> ➡️ <code>const struct timespec *rqtp</code>
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
