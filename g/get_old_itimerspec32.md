# Function: <code>get_old_itimerspec32</code>

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
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c210)
Location: kernel/time/time.c:901
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime
  - fs/timerfd.c:__x32_compat_sys_timerfd_settime
  - fs/timerfd.c:__ia32_compat_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111c210-ffffffff8111c2a4: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126c00)
Location: kernel/time/time.c:979
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81126c00-ffffffff81126c9b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132ba0)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81132ba0-ffffffff81132c3b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142210)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81142210-ffffffff811422ab: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e420)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8113e420-ffffffff8113e4bb: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f670)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8113f670-ffffffff8113f70b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162b00)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81162b00-ffffffff81162b9b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195ad0)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81195ad0-ffffffff81195b82: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3a10)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811d3a10-ffffffff811d3ac2: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7d00)
Location: kernel/time/time.c:890
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811e7d00-ffffffff811e7db2: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fda30)
Location: kernel/time/time.c:1029
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811fda30-ffffffff811fdae2: get_old_itimerspec32 (STB_GLOBAL)
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
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019aa88)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - fs/timerfd.c:__arm64_sys_timerfd_settime32
```
**Symbols:**

```
ffff80001019aa88-ffff80001019ab20: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e50ec)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - fs/timerfd.c:__se_sys_timerfd_settime32
```
**Symbols:**

```
c03e50ec-c03e521c: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa7c0)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - fs/timerfd.c:__se_sys_timerfd_settime32
```
**Symbols:**

```
c0000000001fa7c0-c0000000001fa890: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a7b2)
Location: kernel/time/time.c:980
Inline: False
```
**Symbols:**

```
ffffffe00012a7b2-ffffffe00012a81e: get_old_itimerspec32 (STB_GLOBAL)
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
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b350)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8112b350-ffffffff8112b3eb: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111dbc0)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff8111dbc0-ffffffff8111dc5b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129070)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff81129070-ffffffff8112910b: get_old_itimerspec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_old_itimerspec32(struct itimerspec64 *its, const struct old_itimerspec32 *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811356c0)
Location: kernel/time/time.c:980
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - fs/timerfd.c:__ia32_sys_timerfd_settime32
  - fs/timerfd.c:__x64_sys_timerfd_settime32
```
**Symbols:**

```
ffffffff811356c0-ffffffff8113575b: get_old_itimerspec32 (STB_GLOBAL)
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
