# Function: <code>put_compat_itimerspec64</code>

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
int put_compat_itimerspec64(const struct itimerspec *its, struct compat_itimerspec *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120410)
Location: kernel/compat.c:422
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_settime
  - kernel/time/posix-timers.c:compat_SyS_timer_gettime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:compat_SyS_timerfd_settime
```
**Symbols:**

```
ffffffff81120410-ffffffff811204a8: put_compat_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_itimerspec64(const struct itimerspec *its, struct compat_itimerspec *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bb40)
Location: kernel/compat.c:381
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_settime
  - kernel/time/posix-timers.c:compat_SyS_timer_gettime
  - fs/timerfd.c:compat_SyS_timerfd_gettime
  - fs/timerfd.c:compat_SyS_timerfd_settime
```
**Symbols:**

```
ffffffff8112bb40-ffffffff8112bbd8: put_compat_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_compat_itimerspec64(const struct itimerspec64 *its, struct compat_itimerspec *uits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a470)
Location: kernel/compat.c:346
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
ffffffff8113a470-ffffffff8113a4a9: put_compat_itimerspec64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<code>const struct itimerspec *its</code> ➡️ <code>const struct itimerspec64 *its</code>
</li>
</ul>
</details>
</li>
</ul>
