# Function: <code>posix_cpu_clock_getres</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2b20)
Location: kernel/time/posix-cpu-timers.c:144
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
**Symbols:**

```
ffffffff810f2b20-ffffffff810f2b60: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9ca6)
Location: kernel/time/posix-cpu-timers.c:144
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff810f9c30-ffffffff810f9c70: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107636)
Location: kernel/time/posix-cpu-timers.c:143
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811075c0-ffffffff81107600: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109996)
Location: kernel/time/posix-cpu-timers.c:124
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81109950-ffffffff81109990: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114b76)
Location: kernel/time/posix-cpu-timers.c:125
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81114b30-ffffffff81114b70: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121315)
Location: kernel/time/posix-cpu-timers.c:126
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811212d0-ffffffff81121310: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112ca35)
Location: kernel/time/posix-cpu-timers.c:126
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff8112c9f0-ffffffff8112ca30: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137405)
Location: kernel/time/posix-cpu-timers.c:126
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811373c0-ffffffff81137400: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143320)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81143320-ffffffff81143376: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152b45)
Location: kernel/time/posix-cpu-timers.c:153
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81152830-ffffffff81152884: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114edb5)
Location: kernel/time/posix-cpu-timers.c:153
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff8114ea80-ffffffff8114eade: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150245)
Location: kernel/time/posix-cpu-timers.c:153
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff8114ff10-ffffffff8114ff6e: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81174495)
Location: kernel/time/posix-cpu-timers.c:153
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81174100-ffffffff8117415e: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a929d)
Location: kernel/time/posix-cpu-timers.c:160
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811a8e20-ffffffff811a8e87: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e910d)
Location: kernel/time/posix-cpu-timers.c:160
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811e8c80-ffffffff811e8ce7: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fd6fd)
Location: kernel/time/posix-cpu-timers.c:160
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811fd290-ffffffff811fd2f7: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff812138fd)
Location: kernel/time/posix-cpu-timers.c:160
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff81213490-ffffffff812134f7: posix_cpu_clock_getres (STB_LOCAL)
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
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad460)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffff8000101ad460-ffff8000101ad4dc: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f83c0)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
c03f83c0-c03f8428: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000211760)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
c000000000211760-c00000000021180c: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013743e)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffe00013743e-ffffffe0001374a6: posix_cpu_clock_getres (STB_LOCAL)
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
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113bad0)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff8113bad0-ffffffff8113bb26: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112e490)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff8112e490-ffffffff8112e4e6: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811397f0)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811397f0-ffffffff81139846: posix_cpu_clock_getres (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_cpu_clock_getres(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811462c0)
Location: kernel/time/posix-cpu-timers.c:163
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_getres
```
**Symbols:**

```
ffffffff811462c0-ffffffff81146316: posix_cpu_clock_getres (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *tp</code> ➡️ <code>struct timespec64 *tp</code>
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
