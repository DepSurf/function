# Function: <code>do_adjtimex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f6b50)
Location: kernel/time/timekeeping.c:2246
Inline: False
Direct callers:
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
  - kernel/compat.c:C_SYSC_adjtimex
```
**Symbols:**

```
ffffffff810f6b50-ffffffff810f6cbd: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fdcb0)
Location: kernel/time/timekeeping.c:2252
Inline: False
Direct callers:
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
  - kernel/compat.c:C_SYSC_adjtimex
```
**Symbols:**

```
ffffffff810fdcb0-ffffffff810fde29: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100aa0)
Location: kernel/time/timekeeping.c:2264
Inline: False
Direct callers:
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
  - kernel/compat.c:C_SYSC_adjtimex
```
**Symbols:**

```
ffffffff81100aa0-ffffffff81100c19: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81102be0)
Location: kernel/time/timekeeping.c:2253
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81102be0-ffffffff81102d59: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110db90)
Location: kernel/time/timekeeping.c:2348
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8110db90-ffffffff8110de38: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81119580)
Location: kernel/time/timekeeping.c:2289
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81119580-ffffffff811197fb: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_adjtimex(struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124a70)
Location: kernel/time/timekeeping.c:2303
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81124a70-ffffffff81124cff: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f3b0)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8112f3b0-ffffffff8112f6df: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113b370)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8113b370-ffffffff8113b69f: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114a3c0)
Location: kernel/time/timekeeping.c:2312
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8114a3c0-ffffffff8114a6e8: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146910)
Location: kernel/time/timekeeping.c:2375
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81146910-ffffffff81146c38: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147a80)
Location: kernel/time/timekeeping.c:2386
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81147a80-ffffffff81147da8: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116b5a0)
Location: kernel/time/timekeeping.c:2387
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8116b5a0-ffffffff8116b8e9: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119f4c0)
Location: kernel/time/timekeeping.c:2422
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8119f4c0-ffffffff8119f809: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811de1c0)
Location: kernel/time/timekeeping.c:2422
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff811de1c0-ffffffff811de512: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f2690)
Location: kernel/time/timekeeping.c:2422
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff811f2690-ffffffff811f29e2: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff812087d0)
Location: kernel/time/timekeeping.c:2422
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff812087d0-ffffffff81208b22: do_adjtimex (STB_GLOBAL)
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
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a5580)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffff8000101a5580-ffff8000101a5914: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03f05b4)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
c03f05b4-c03f0940: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002073b0)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
c0000000002073b0-c000000000207800: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe0001319ca)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffe0001319ca-ffffffe000131c8c: do_adjtimex (STB_GLOBAL)
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
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133b20)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81133b20-ffffffff81133e4f: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81126580)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81126580-ffffffff811268af: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131840)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff81131840-ffffffff81131b6f: do_adjtimex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_adjtimex(struct __kernel_timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113e260)
Location: kernel/time/timekeeping.c:2313
Inline: False
Direct callers:
  - kernel/time/time.c:__do_sys_adjtimex_time32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_adj
```
**Symbols:**

```
ffffffff8113e260-ffffffff8113e58f: do_adjtimex (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timex *txc</code> ➡️ <code>struct __kernel_timex *txc</code>
</li>
</ul>
</details>
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
