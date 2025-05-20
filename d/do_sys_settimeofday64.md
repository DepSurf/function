# Function: <code>do_sys_settimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1fb0)
Location: kernel/time/time.c:163
Inline: True
Direct callers:
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
  - kernel/time/posix-timers.c:posix_clock_realtime_set
  - kernel/compat.c:compat_SyS_settimeofday
  - kernel/compat.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff810f1fb0-ffffffff810f20b6: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f9130)
Location: kernel/time/time.c:163
Inline: True
Direct callers:
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
  - kernel/time/posix-timers.c:posix_clock_realtime_set
  - kernel/compat.c:compat_SyS_settimeofday
  - kernel/compat.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff810f9130-ffffffff810f9236: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb4e0)
Location: kernel/time/time.c:205
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_settimeofday
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff810fb4e0-ffffffff810fb5ef: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105e80)
Location: kernel/time/time.c:171
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_settimeofday
  - kernel/time/time.c:SyS_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81105e80-ffffffff81105f3b: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81111290)
Location: kernel/time/time.c:172
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81111290-ffffffff8111134a: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c9a0)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff8111c9a0-ffffffff8111ca5a: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811272d0)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff811272d0-ffffffff81127398: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81133270)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81133270-ffffffff81133338: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142590)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81142590-ffffffff81142658: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e7a0)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff8113e7a0-ffffffff8113e868: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f9d0)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff8113f9d0-ffffffff8113fa98: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162e60)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x64_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81162e60-ffffffff81162f28: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195eb0)
Location: kernel/time/time.c:169
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81195eb0-ffffffff81195f8c: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3e40)
Location: kernel/time/time.c:169
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff811d3e40-ffffffff811d3f1c: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8130)
Location: kernel/time/time.c:169
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff811e8130-ffffffff811e820c: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fde60)
Location: kernel/time/time.c:169
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff811fde60-ffffffff811fdf3c: do_sys_settimeofday64 (STB_GLOBAL)
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
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019ba30)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__arm64_compat_sys_settimeofday
  - kernel/time/time.c:__arm64_compat_sys_settimeofday
  - kernel/time/time.c:__arm64_compat_sys_settimeofday
  - kernel/time/time.c:__arm64_sys_settimeofday
  - kernel/time/time.c:__arm64_sys_settimeofday
  - kernel/time/time.c:__arm64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffff80001019ba30-ffff80001019bb10: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e56bc)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
c03e56bc-c03e57c8: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fb400)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__se_compat_sys_settimeofday
  - kernel/time/time.c:__se_compat_sys_settimeofday
  - kernel/time/time.c:__se_compat_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
c0000000001fb400-c0000000001fb57c: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012aa8c)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffe00012aa8c-ffffffe00012ab52: do_sys_settimeofday64 (STB_GLOBAL)
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
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ba20)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff8112ba20-ffffffff8112bae8: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111e290)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff8111e290-ffffffff8111e358: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129740)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81129740-ffffffff81129808: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_sys_settimeofday64(const struct timespec64 *tv, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135d90)
Location: kernel/time/time.c:169
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
**Symbols:**

```
ffffffff81135d90-ffffffff81135e58: do_sys_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>const struct timespec *tv</code> ➡️ <code>const struct timespec64 *tv</code>
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
