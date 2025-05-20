# Function: <code>do_timer_settime</code>

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
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec *new_spec64, struct itimerspec *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107b10)
Location: kernel/time/posix-timers.c:866
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_settime
```
**Symbols:**

```
ffffffff81107b10-ffffffff81107c20: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec *new_spec64, struct itimerspec *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112c80)
Location: kernel/time/posix-timers.c:872
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_settime
```
**Symbols:**

```
ffffffff81112c80-ffffffff81112d92: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111f360)
Location: kernel/time/posix-timers.c:881
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8111f360-ffffffff8111f47a: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112ab30)
Location: kernel/time/posix-timers.c:847
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8112ab30-ffffffff8112ac4a: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_timer_settime(timer_t timer_id, int flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81135300)
Location: kernel/time/posix-timers.c:847
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff81135300-ffffffff81135428: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81141470)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff81141320-ffffffff81141401: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8115012b)
Location: kernel/time/posix-timers.c:898
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8114ffe0-ffffffff811500c1: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114c66b)
Location: kernel/time/posix-timers.c:898
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8114c260-ffffffff8114c341: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d86d)
Location: kernel/time/posix-timers.c:898
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8114d720-ffffffff8114d807: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8117163d)
Location: kernel/time/posix-timers.c:898
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff811714f0-ffffffff811715d7: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5ad0)
Location: kernel/time/posix-timers.c:898
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff811a5ad0-ffffffff811a5bf6: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e55a0)
Location: kernel/time/posix-timers.c:898
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff811e55a0-ffffffff811e56c6: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9c00)
Location: kernel/time/posix-timers.c:900
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff811f9c00-ffffffff811f9d26: do_timer_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_timer_settime(timer_t timer_id, int tmr_flags, struct itimerspec64 *new_spec64, struct itimerspec64 *old_spec64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120fdf0)
Location: kernel/time/posix-timers.c:900
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8120fdf0-ffffffff8120ff16: do_timer_settime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101abf80)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
```
**Symbols:**

```
ffff8000101abd28-ffff8000101abe20: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (c03f6ef4)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
**Symbols:**

```
c03f63f8-c03f6528: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (c0000000002105e0)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
**Symbols:**

```
c00000000020fac0-c00000000020fbf0: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000136754)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81139c20)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff81139ad0-ffffffff81139bb1: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112c670)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff8112c520-ffffffff8112c601: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81137940)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff811377f0-ffffffff811378d1: do_timer_settime.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811443d0)
Location: kernel/time/posix-timers.c:876
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
Direct callers:
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
**Symbols:**

```
ffffffff81144280-ffffffff81144361: do_timer_settime.part.0 (STB_LOCAL)
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
<code>struct itimerspec *new_spec64</code> ➡️ <code>struct itimerspec64 *new_spec64</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerspec *old_spec64</code> ➡️ <code>struct itimerspec64 *old_spec64</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
