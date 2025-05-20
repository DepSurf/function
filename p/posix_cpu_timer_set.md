# Function: <code>posix_cpu_timer_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f3110)
Location: kernel/time/posix-cpu-timers.c:624
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff810f3110-ffffffff810f343a: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810fa220)
Location: kernel/time/posix-cpu-timers.c:594
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff810fa220-ffffffff810fa54d: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107ba0)
Location: kernel/time/posix-cpu-timers.c:590
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81107ba0-ffffffff81107ecd: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81109e60)
Location: kernel/time/posix-cpu-timers.c:572
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81109e60-ffffffff8110a12f: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec *new, struct itimerspec *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81115030)
Location: kernel/time/posix-cpu-timers.c:573
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81115030-ffffffff811152e8: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811217c0)
Location: kernel/time/posix-cpu-timers.c:574
Inline: False
```
**Symbols:**

```
ffffffff811217c0-ffffffff81121a84: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112cee0)
Location: kernel/time/posix-cpu-timers.c:574
Inline: False
```
**Symbols:**

```
ffffffff8112cee0-ffffffff8112d1a8: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811378a0)
Location: kernel/time/posix-cpu-timers.c:574
Inline: False
```
**Symbols:**

```
ffffffff811378a0-ffffffff81137bfa: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143800)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffffffff81143800-ffffffff81143b6c: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81152f10)
Location: kernel/time/posix-cpu-timers.c:560
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81152f10-ffffffff8115326d: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114f1b0)
Location: kernel/time/posix-cpu-timers.c:572
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff8114f1b0-ffffffff8114f517: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150640)
Location: kernel/time/posix-cpu-timers.c:572
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81150640-ffffffff811509a7: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81174910)
Location: kernel/time/posix-cpu-timers.c:617
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81174910-ffffffff81174d5f: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a9750)
Location: kernel/time/posix-cpu-timers.c:624
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811a9750-ffffffff811a9bc8: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e96a0)
Location: kernel/time/posix-cpu-timers.c:624
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811e96a0-ffffffff811e9b18: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fdd90)
Location: kernel/time/posix-cpu-timers.c:623
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff811fdd90-ffffffff811fe208: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81214160)
Location: kernel/time/posix-cpu-timers.c:623
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffff81214160-ffffffff812145a0: posix_cpu_timer_set (STB_LOCAL)
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
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101adce8)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffff8000101adce8-ffff8000101adf8c: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f8c94)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
c03f8c94-c03f9008: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000211f80)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
c000000000211f80-c0000000002123b0: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe0001379fc)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
**Symbols:**

```
ffffffe0001379fc-ffffffe000137c54: posix_cpu_timer_set (STB_LOCAL)
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
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113bfb0)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffffffff8113bfb0-ffffffff8113c31c: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112ea70)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffffffff8112ea70-ffffffff8112eddc: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81139cd0)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffffffff81139cd0-ffffffff8113a03c: posix_cpu_timer_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_cpu_timer_set(struct k_itimer *timer, int timer_flags, struct itimerspec64 *new, struct itimerspec64 *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811467c0)
Location: kernel/time/posix-cpu-timers.c:561
Inline: False
```
**Symbols:**

```
ffffffff811467c0-ffffffff81146b2c: posix_cpu_timer_set (STB_LOCAL)
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
<code>struct itimerspec *new</code> ➡️ <code>struct itimerspec64 *new</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerspec *old</code> ➡️ <code>struct itimerspec64 *old</code>
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
