# Function: <code>hrtimer_nanosleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec *rqtp, struct timespec *rmtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810efdc0)
Location: kernel/time/hrtimer.c:1545
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_nanosleep
```
**Symbols:**

```
ffffffff810efdc0-ffffffff810effc3: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec *rqtp, struct timespec *rmtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f6c00)
Location: kernel/time/hrtimer.c:1535
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_nanosleep
```
**Symbols:**

```
ffffffff810f6c00-ffffffff810f6e05: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int hrtimer_nanosleep(struct timespec *rqtp, struct timespec *rmtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fdcb0)
Location: kernel/time/hrtimer.c:1535
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_nanosleep
```
**Symbols:**

```
ffffffff810fdcb0-ffffffff810fdec8: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fff70)
Location: kernel/time/hrtimer.c:1513
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff810fff70-ffffffff81100141: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110ad60)
Location: kernel/time/hrtimer.c:1518
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff8110ad60-ffffffff8110af33: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116750)
Location: kernel/time/hrtimer.c:1729
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81116750-ffffffff81116937: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121d90)
Location: kernel/time/hrtimer.c:1719
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81121d90-ffffffff81121f77: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112c6e0)
Location: kernel/time/hrtimer.c:1719
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff8112c6e0-ffffffff8112c8ba: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81138700)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81138700-ffffffff81138897: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81147510)
Location: kernel/time/hrtimer.c:1918
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81147510-ffffffff811476cb: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143a20)
Location: kernel/time/hrtimer.c:1935
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81143a20-ffffffff81143b52: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144bd0)
Location: kernel/time/hrtimer.c:1935
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81144bd0-ffffffff81144ce9: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81168420)
Location: kernel/time/hrtimer.c:2083
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81168420-ffffffff81168539: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119be50)
Location: kernel/time/hrtimer.c:2083
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff8119be50-ffffffff8119c00a: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811da7c0)
Location: kernel/time/hrtimer.c:2083
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff811da7c0-ffffffff811da97a: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811eecf0)
Location: kernel/time/hrtimer.c:2086
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff811eecf0-ffffffff811eee88: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int hrtimer_nanosleep(ktime_t rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81204e70)
Location: kernel/time/hrtimer.c:2087
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81204e70-ffffffff81205008: hrtimer_nanosleep (STB_GLOBAL)
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
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a23a0)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffff8000101a23a0-ffff8000101a2530: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ec0ac)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
c03ec0ac-c03ec2a0: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000203880)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__se_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
c000000000203880-c000000000203a38: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f4cc)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffe00012f4cc-ffffffe00012f5e2: hrtimer_nanosleep (STB_GLOBAL)
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
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130eb0)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81130eb0-ffffffff81131047: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81123920)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff81123920-ffffffff81123ab7: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ebd0)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff8112ebd0-ffffffff8112ed67: hrtimer_nanosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int hrtimer_nanosleep(const struct timespec64 *rqtp, const enum hrtimer_mode mode, const clockid_t clockid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113b5d0)
Location: kernel/time/hrtimer.c:1913
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:common_nsleep
```
**Symbols:**

```
ffffffff8113b5d0-ffffffff8113b767: hrtimer_nanosleep (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>rqtp, rmtp, mode, clockid</code> ➡️ <code>rqtp, mode, clockid</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec64 *rqtp</code> ➡️ <code>ktime_t rqtp</code>
</li>
</ul>
</details>
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
