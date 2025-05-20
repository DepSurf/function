# Function: <code>do_sigtimedwait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, siginfo_t *info, const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091200)
Location: kernel/signal.c:2749
Inline: False
Direct callers:
  - kernel/signal.c:SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81091200-ffffffff8109140c: do_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, siginfo_t *info, const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094360)
Location: kernel/signal.c:2753
Inline: False
Direct callers:
  - kernel/signal.c:SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81094360-ffffffff81094579: do_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, siginfo_t *info, const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099350)
Location: kernel/signal.c:2766
Inline: False
Direct callers:
  - kernel/signal.c:SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81099350-ffffffff8109956a: do_sigtimedwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, siginfo_t *info, const struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810930b0)
Location: kernel/signal.c:2787
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - kernel/signal.c:SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810930b0-ffffffff810932d3: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, siginfo_t *info, const struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099f90)
Location: kernel/signal.c:2810
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - kernel/signal.c:SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81099f90-ffffffff8109a1b6: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8109df80)
Location: kernel/signal.c:3041
Inline: True
Direct callers:
  - kernel/signal.c:__do_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__do_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff8109df80-ffffffff8109e1ab: do_sigtimedwait.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810a6290)
Location: kernel/signal.c:3303
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810a6290-ffffffff810a64a9: do_sigtimedwait.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810aaf90)
Location: kernel/signal.c:3432
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810aaf90-ffffffff810ab186: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810b1590)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810b1590-ffffffff810b1786: do_sigtimedwait.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b90b0)
Location: kernel/signal.c:3455
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810b90b0-ffffffff810b92a4: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4360)
Location: kernel/signal.c:3475
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810b4360-ffffffff810b4554: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5f70)
Location: kernel/signal.c:3497
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810b5f70-ffffffff810b6165: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8e00)
Location: kernel/signal.c:3585
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810c8e00-ffffffff810c8ff5: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e0380)
Location: kernel/signal.c:3567
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810e0380-ffffffff810e0597: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81100a20)
Location: kernel/signal.c:3569
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81100a20-ffffffff81100bf9: do_sigtimedwait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8110cb20)
Location: kernel/signal.c:3593
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff8110cb20-ffffffff8110ccf6: do_sigtimedwait.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff81116500)
Location: kernel/signal.c:3604
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff81116500-ffffffff811166d6: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffff80001010d1c8)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffff80001010d1c8-ffff80001010d428: do_sigtimedwait.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t *which, kernel_siginfo_t *info, const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036546c)
Location: kernel/signal.c:3437
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
**Symbols:**

```
c036546c-c0365720: do_sigtimedwait (STB_LOCAL)
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
In kernel/signal.c (c0000000001542c0)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
**Symbols:**

```
c0000000001542c0-c0000000001545cc: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000d1394)
Location: kernel/signal.c:3437
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810ab900)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810ab900-ffffffff810abaf6: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff8109a2a0)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff8109a2a0-ffffffff8109a48a: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aae60)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810aae60-ffffffff810ab056: do_sigtimedwait.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810b2f40)
Location: kernel/signal.c:3437
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810b2f40-ffffffff810b3134: do_sigtimedwait.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
