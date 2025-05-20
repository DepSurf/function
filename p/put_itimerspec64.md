# Function: <code>put_itimerspec64</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec *it, struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fae60)
Location: kernel/time/time.c:937
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff810fae60-ffffffff810faefc: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec *it, struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811057f0)
Location: kernel/time/time.c:886
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff811057f0-ffffffff8110588c: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811108b0)
Location: kernel/time/time.c:948
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811108b0-ffffffff8111094c: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111be40)
Location: kernel/time/time.c:886
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111be40-ffffffff8111bedc: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126880)
Location: kernel/time/time.c:964
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81126880-ffffffff8112691c: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132820)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81132820-ffffffff811328bc: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811424f0)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811424f0-ffffffff8114258a: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e700)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8113e700-ffffffff8113e79a: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f930)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8113f930-ffffffff8113f9c7: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162dc0)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81162dc0-ffffffff81162e57: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195d10)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81195d10-ffffffff81195db1: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3c80)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811d3c80-ffffffff811d3d21: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7f70)
Location: kernel/time/time.c:875
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811e7f70-ffffffff811e8011: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdca0)
Location: kernel/time/time.c:1007
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811fdca0-ffffffff811fdd41: put_itimerspec64 (STB_GLOBAL)
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
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019b050)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
  - kernel/time/posix-timers.c:__arm64_sys_timer_gettime
  - fs/timerfd.c:__arm64_sys_timerfd_gettime
  - fs/timerfd.c:__arm64_sys_timerfd_settime
```
**Symbols:**

```
ffff80001019b050-ffff80001019b328: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4dd0)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c03e4dd0-c03e4e08: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa470)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c0000000001fa470-c0000000001fa540: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a5e2)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_gettime
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
ffffffe00012a5e2-ffffffe00012a64a: put_itimerspec64 (STB_GLOBAL)
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
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112afd0)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8112afd0-ffffffff8112b06c: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d840)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111d840-ffffffff8111d8dc: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128cf0)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81128cf0-ffffffff81128d8c: put_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_itimerspec64(const struct itimerspec64 *it, struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135340)
Location: kernel/time/time.c:965
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_gettime
  - fs/timerfd.c:__x64_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81135340-ffffffff811353dc: put_itimerspec64 (STB_GLOBAL)
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
<code>const struct itimerspec *it</code> ➡️ <code>const struct itimerspec64 *it</code>
</li>
</ul>
</details>
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
<code>struct itimerspec *uit</code> ➡️ <code>struct __kernel_itimerspec *uit</code>
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
