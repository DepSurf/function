# Function: <code>set_normalized_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec(struct timespec *ts, time_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eac80)
Location: kernel/time/time.c:361
Inline: True
Inline callers:
  - kernel/time/time.c:timespec_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - fs/select.c:poll_select_copy_remaining
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810eac80-ffffffff810eacc1: set_normalized_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec(struct timespec *ts, time_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f226d)
Location: kernel/time/time.c:368
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
  - kernel/time/time.c:timespec_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_copy_remaining
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810f1920-ffffffff810f1961: set_normalized_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec(struct timespec *ts, time_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f93ed)
Location: kernel/time/time.c:368
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
  - kernel/time/time.c:timespec_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_copy_remaining
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810f8aa0-ffffffff810f8ae1: set_normalized_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec(struct timespec *ts, time_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb8fd)
Location: kernel/time/time.c:458
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
  - kernel/time/time.c:timespec_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810faac0-ffffffff810fab01: set_normalized_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_normalized_timespec(struct timespec *ts, time_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110260)
Location: kernel/time/time.c:426
Inline: False
```
**Symbols:**

```
ffffffff81110260-ffffffff811102a1: set_normalized_timespec (STB_GLOBAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
