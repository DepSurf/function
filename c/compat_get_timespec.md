# Function: <code>compat_get_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110ff60)
Location: kernel/compat.c:175
Inline: True
Direct callers:
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_clock_settime
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_io_getevents
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8110ff60-ffffffff8110ff9d: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811172f0)
Location: kernel/compat.c:175
Inline: False
Direct callers:
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:compat_SyS_clock_settime
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_convert_timespec
  - fs/compat.c:compat_SyS_io_getevents
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utimensat
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff811172f0-ffffffff8111732d: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111ea30)
Location: kernel/compat.c:175
Inline: False
Direct callers:
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:compat_SyS_clock_settime
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_convert_timespec
  - fs/aio.c:compat_SyS_io_getevents
  - fs/compat.c:compat_SyS_utimensat
  - fs/compat.c:compat_SyS_utimensat
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8111ea30-ffffffff8111ea6d: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811206c0)
Location: kernel/compat.c:185
Inline: True
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/compat.c:compat_convert_timespec
  - fs/utimes.c:compat_SyS_utimensat
  - fs/utimes.c:compat_SyS_utimensat
  - fs/aio.c:compat_SyS_io_getevents
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff811206c0-ffffffff811206fd: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bdf0)
Location: kernel/compat.c:185
Inline: True
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - kernel/futex_compat.c:compat_SyS_futex
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8112bdf0-ffffffff8112be67: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a5b0)
Location: kernel/compat.c:142
Inline: True
Direct callers:
  - kernel/signal.c:__do_compat_sys_rt_sigtimedwait
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
```
**Symbols:**

```
ffffffff8113a5b0-ffffffff8113a627: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145e10)
Location: kernel/compat.c:142
Inline: True
```
**Symbols:**

```
ffffffff81145e10-ffffffff81145e87: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151150)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff81151150-ffffffff811511d0: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115cdc0)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff8115cdc0-ffffffff8115ce40: compat_get_timespec (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cbe18)
Location: kernel/compat.c:75
Inline: False
```
**Symbols:**

```
ffff8000101cbe18-ffff8000101cc110: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236980)
Location: kernel/compat.c:75
Inline: False
```
**Symbols:**

```
c000000000236980-c000000000236a98: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811553e0)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff811553e0-ffffffff81155460: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148700)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff81148700-ffffffff81148780: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811531b0)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff811531b0-ffffffff81153230: compat_get_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811600b0)
Location: kernel/compat.c:75
Inline: True
```
**Symbols:**

```
ffffffff811600b0-ffffffff81160130: compat_get_timespec (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
