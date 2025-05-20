# Function: <code>compat_put_timespec64</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec64(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120540)
Location: kernel/compat.c:158
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
```
**Symbols:**

```
ffffffff81120540-ffffffff811205be: compat_put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec64(const struct timespec *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bc70)
Location: kernel/compat.c:158
Inline: True
Direct callers:
  - kernel/sched/core.c:compat_SyS_sched_rr_get_interval
  - kernel/time/posix-timers.c:compat_SyS_clock_getres
  - kernel/time/posix-timers.c:compat_SyS_clock_gettime
  - fs/select.c:compat_poll_select_copy_remaining
```
**Symbols:**

```
ffffffff8112bc70-ffffffff8112bcee: compat_put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_put_timespec64(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110f20)
Location: kernel/time/time.c:924
Inline: True
Direct callers:
  - kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - fs/select.c:compat_poll_select_copy_remaining
```
**Symbols:**

```
ffffffff81110f20-ffffffff81110f9e: compat_put_timespec64 (STB_GLOBAL)
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
<code>const struct timespec *ts</code> ➡️ <code>const struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
</ul>
