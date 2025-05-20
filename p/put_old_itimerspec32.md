# Function: <code>put_old_itimerspec32</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111bee0)
Location: kernel/time/time.c:912
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_gettime
  - fs/timerfd.c:__x32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_gettime
  - fs/timerfd.c:__x32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111bee0-ffffffff8111bf78: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126920)
Location: kernel/time/time.c:990
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81126920-ffffffff811269b8: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811328c0)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811328c0-ffffffff81132958: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142170)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81142170-ffffffff81142206: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e380)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8113e380-ffffffff8113e416: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f5d0)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8113f5d0-ffffffff8113f663: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162a60)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81162a60-ffffffff81162af3: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195a30)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81195a30-ffffffff81195aca: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3960)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811d3960-ffffffff811d39fa: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7c50)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811e7c50-ffffffff811e7cea: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fd980)
Location: kernel/time/time.c:1048
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811fd980-ffffffff811fda1a: put_old_itimerspec32 (STB_GLOBAL)
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
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019b328)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_gettime32
  - fs/timerfd.c:__arm64_sys_timerfd_gettime32
  - fs/timerfd.c:__arm64_sys_timerfd_settime32
```
**Symbols:**

```
ffff80001019b328-ffff80001019b600: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4e08)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_gettime32
  - fs/timerfd.c:__se_sys_timerfd_gettime32
  - fs/timerfd.c:__se_sys_timerfd_settime32
```
**Symbols:**

```
c03e4e08-c03e4f34: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa540)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_gettime32
  - fs/timerfd.c:__se_sys_timerfd_gettime32
  - fs/timerfd.c:__se_sys_timerfd_settime32
```
**Symbols:**

```
c0000000001fa540-c0000000001fa610: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a64a)
Location: kernel/time/time.c:991
Inline: False
```
**Symbols:**

```
ffffffe00012a64a-ffffffe00012a6b2: put_old_itimerspec32 (STB_GLOBAL)
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
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b070)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8112b070-ffffffff8112b108: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d8e0)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8111d8e0-ffffffff8111d978: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128d90)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81128d90-ffffffff81128e28: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_old_itimerspec32(const struct itimerspec64 *its, struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811353e0)
Location: kernel/time/time.c:991
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_gettime32
  - kernel/time/posix-timers.c:__x64_sys_timer_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_gettime32
  - fs/timerfd.c:__x64_sys_timerfd_gettime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811353e0-ffffffff81135478: put_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
