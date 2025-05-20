# Function: <code>do_settimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f5140)
Location: kernel/time/timekeeping.c:1157
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff810f5140-ffffffff810f5291: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc300)
Location: kernel/time/timekeeping.c:1162
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff810fc300-ffffffff810fc450: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff200)
Location: kernel/time/timekeeping.c:1191
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff810ff200-ffffffff810ff350: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811011d0)
Location: kernel/time/timekeeping.c:1221
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff811011d0-ffffffff8110132a: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_settimeofday64(const struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c000)
Location: kernel/time/timekeeping.c:1225
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff8110c000-ffffffff8110c15a: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118090)
Location: kernel/time/timekeeping.c:1226
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__x32_compat_sys_stime
  - kernel/time/time.c:__ia32_compat_sys_stime
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff81118090-ffffffff811181e9: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811236b0)
Location: kernel/time/timekeeping.c:1217
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__x32_compat_sys_stime
  - kernel/time/time.c:__ia32_compat_sys_stime
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff811236b0-ffffffff81123809: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112e160)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff8112e160-ffffffff8112e30b: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113a110)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff8113a110-ffffffff8113a2bb: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148f40)
Location: kernel/time/timekeeping.c:1223
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff81148f40-ffffffff811490b6: do_settimeofday64.part.0 (STB_LOCAL)
ffffffff811490c0-ffffffff811490fd: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811453b0)
Location: kernel/time/timekeeping.c:1292
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff811453b0-ffffffff81145526: do_settimeofday64.part.0 (STB_LOCAL)
ffffffff81145530-ffffffff8114556d: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811460d0)
Location: kernel/time/timekeeping.c:1293
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff811460d0-ffffffff81146279: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116a4c0)
Location: kernel/time/timekeeping.c:1293
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff8116a320-ffffffff8116a4b6: do_settimeofday64.part.0 (STB_LOCAL)
ffffffff81cb0f5a-ffffffff81cb0f99: do_settimeofday64.part.0.cold (STB_LOCAL)
ffffffff8116a4c0-ffffffff8116a4fd: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1312
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81e62825-ffffffff81e62864: do_settimeofday64.cold (STB_LOCAL)
ffffffff8119e940-ffffffff8119eb46: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1312
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff8205b584-ffffffff8205b5c3: do_settimeofday64.cold (STB_LOCAL)
ffffffff811dd370-ffffffff811dd576: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1312
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff820d9e1d-ffffffff820d9e5c: do_settimeofday64.cold (STB_LOCAL)
ffffffff811f1870-ffffffff811f1a76: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1312
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff821b571c-ffffffff821b575b: do_settimeofday64.cold (STB_LOCAL)
ffffffff812079b0-ffffffff81207bb6: do_settimeofday64 (STB_GLOBAL)
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
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a4518)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/arm/xen/enlighten.c:xen_pm_init
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffff8000101a4518-ffff8000101a4738: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ee52c)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
c03ee52c-c03ee7f8: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205f90)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
c000000000205f90-c0000000002061fc: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130bbe)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffe000130bbe-ffffffe000130cfe: do_settimeofday64.part.0 (STB_LOCAL)
ffffffe000130cfe-ffffffe000130d4c: do_settimeofday64 (STB_GLOBAL)
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
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811328c0)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff811328c0-ffffffff81132a6b: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125320)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff81125320-ffffffff811254cb: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811305e0)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff811305e0-ffffffff8113078b: do_settimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_settimeofday64(const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113d000)
Location: kernel/time/timekeeping.c:1224
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
  - drivers/rtc/hctosys.c:rtc_hctosys
```
**Symbols:**

```
ffffffff8113d000-ffffffff8113d1ab: do_settimeofday64 (STB_GLOBAL)
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
