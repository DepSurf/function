# Function: <code>posix_cpu_nsleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3730)
Location: kernel/time/posix-cpu-timers.c:1382
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff810f3730-ffffffff810f3840: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fa850)
Location: kernel/time/posix-cpu-timers.c:1353
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff810fa850-ffffffff810fa978: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, struct timespec *rqtp, struct timespec *rmtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811081d0)
Location: kernel/time/posix-cpu-timers.c:1349
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff811081d0-ffffffff811082f8: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8110a390)
Location: kernel/time/posix-cpu-timers.c:1330
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8110a390-ffffffff8110a429: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115550)
Location: kernel/time/posix-cpu-timers.c:1329
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81115550-ffffffff811155e9: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121cf0)
Location: kernel/time/posix-cpu-timers.c:1346
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81121cf0-ffffffff81121d89: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112d410)
Location: kernel/time/posix-cpu-timers.c:1344
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8112d410-ffffffff8112d4a9: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137e10)
Location: kernel/time/posix-cpu-timers.c:1343
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81137e10-ffffffff81137ea9: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143e80)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81143e80-ffffffff81143f19: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811539a5)
Location: kernel/time/posix-cpu-timers.c:1296
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81153890-ffffffff81153929: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe13)
Location: kernel/time/posix-cpu-timers.c:1462
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8114fcd0-ffffffff8114fd88: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81151243)
Location: kernel/time/posix-cpu-timers.c:1462
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81151110-ffffffff811511bc: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175613)
Location: kernel/time/posix-cpu-timers.c:1534
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff811754e0-ffffffff8117558c: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a9f53)
Location: kernel/time/posix-cpu-timers.c:1541
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff811a9e00-ffffffff811a9ec8: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e9ee3)
Location: kernel/time/posix-cpu-timers.c:1541
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff811e9d70-ffffffff811e9e38: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fe5f3)
Location: kernel/time/posix-cpu-timers.c:1592
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff811fe480-ffffffff811fe548: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81214983)
Location: kernel/time/posix-cpu-timers.c:1592
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81214810-ffffffff812148d8: posix_cpu_nsleep (STB_LOCAL)
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
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ae3b0)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffff8000101ae3b0-ffff8000101ae46c: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f92a4)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
c03f92a4-c03f9344: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c0000000002128d0)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
c0000000002128d0-c0000000002129d4: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe000137f0c)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffe000137f0c-ffffffe000137fa8: posix_cpu_nsleep (STB_LOCAL)
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
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c630)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8113c630-ffffffff8113c6c9: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f0d0)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8112f0d0-ffffffff8112f169: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a350)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff8113a350-ffffffff8113a3e9: posix_cpu_nsleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_cpu_nsleep(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81146d40)
Location: kernel/time/posix-cpu-timers.c:1317
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
**Symbols:**

```
ffffffff81146d40-ffffffff81146dd9: posix_cpu_nsleep (STB_LOCAL)
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
<code>struct timespec *rmtp</code>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *rqtp</code> ➡️ <code>const struct timespec64 *rqtp</code>
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
