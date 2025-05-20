# Function: <code>get_itimerspec64</code>

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
int get_itimerspec64(struct itimerspec *it, const struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fafe0)
Location: kernel/time/time.c:922
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff810fafe0-ffffffff810fb074: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec *it, const struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105980)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_settime
  - fs/timerfd.c:SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81105980-ffffffff81105a14: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110ac0)
Location: kernel/time/time.c:933
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81110ac0-ffffffff81110b54: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c170)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111c170-ffffffff8111c204: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126bd0)
Location: kernel/time/time.c:949
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81126bd0-ffffffff81126bfe: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132b70)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81132b70-ffffffff81132b9e: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141db0)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81141db0-ffffffff81141dde: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113dfc0)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8113dfc0-ffffffff8113dfee: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f210)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8113f210-ffffffff8113f23e: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811626a0)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811626a0-ffffffff811626ce: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195dc0)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81195dc0-ffffffff81195eab: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3d40)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811d3d40-ffffffff811d3e2b: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8030)
Location: kernel/time/time.c:860
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811e8030-ffffffff811e811b: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdd60)
Location: kernel/time/time.c:984
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff811fdd60-ffffffff811fde4b: get_itimerspec64 (STB_GLOBAL)
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
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a9c0)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
  - fs/timerfd.c:__arm64_sys_timerfd_settime
```
**Symbols:**

```
ffff80001019a9c0-ffff80001019aa04: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e50b4)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c03e50b4-c03e50ec: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa6c0)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
c0000000001fa6c0-c0000000001fa730: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a746)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
ffffffe00012a746-ffffffe00012a7b2: get_itimerspec64 (STB_GLOBAL)
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
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b320)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8112b320-ffffffff8112b34e: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111db90)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff8111db90-ffffffff8111dbbe: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129040)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81129040-ffffffff8112906e: get_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_itimerspec64(struct itimerspec64 *it, const struct __kernel_itimerspec *uit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135690)
Location: kernel/time/time.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - fs/timerfd.c:__ia32_sys_timerfd_settime
  - fs/timerfd.c:__x64_sys_timerfd_settime
```
**Symbols:**

```
ffffffff81135690-ffffffff811356be: get_itimerspec64 (STB_GLOBAL)
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
<code>struct itimerspec *it</code> ➡️ <code>struct itimerspec64 *it</code>
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
<code>const struct itimerspec *uit</code> ➡️ <code>const struct __kernel_itimerspec *uit</code>
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
