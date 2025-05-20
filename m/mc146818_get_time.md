# Function: <code>mc146818_get_time</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff816d6fa0)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
```
**Symbols:**

```
ffffffff816d6fa0-ffffffff816d7153: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81706c80)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81706c80-ffffffff81706e33: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff8171c880)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8171c880-ffffffff8171ca30: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff8178db00)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8178db00-ffffffff8178dcb0: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff817d0110)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817d0110-ffffffff817d02c5: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff817f7270)
Location: drivers/rtc/rtc-mc146818-lib.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817f7270-ffffffff817f7425: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81837f90)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81837f90-ffffffff81838140: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81869900)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81869900-ffffffff81869ab0: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff8193d560)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8193d560-ffffffff8193d710: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81943560)
Location: drivers/rtc/rtc-mc146818-lib.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81943560-ffffffff81943786: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81926d90)
Location: drivers/rtc/rtc-mc146818-lib.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81926d90-ffffffff81926fb6: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff819c9cd0)
Location: drivers/rtc/rtc-mc146818-lib.c:11
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff819c9cd0-ffffffff819c9ef6: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81b2b310)
Location: drivers/rtc/rtc-mc146818-lib.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
**Symbols:**

```
ffffffff81b2b310-ffffffff81b2b430: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81cbf0e0)
Location: drivers/rtc/rtc-mc146818-lib.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
**Symbols:**

```
ffffffff81cbf0e0-ffffffff81cbf201: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81d26a40)
Location: drivers/rtc/rtc-mc146818-lib.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
**Symbols:**

```
ffffffff81d26a40-ffffffff81d26b61: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mc146818_get_time(struct rtc_time *time, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81ddc830)
Location: drivers/rtc/rtc-mc146818-lib.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
**Symbols:**

```
ffffffff81ddc830-ffffffff81ddc951: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (c0b8a7a4)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
```
**Symbols:**

```
c0b8a7a4-c0b8a99c: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8e650)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
```
**Symbols:**

```
c000000000b8e650-c000000000b8ef6c: mc146818_get_time (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff8181c5b0)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8181c5b0-ffffffff8181c760: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff817e3ca0)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817e3ca0-ffffffff817e3e50: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff8185da90)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8185da90-ffffffff8185dc40: mc146818_get_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int mc146818_get_time(struct rtc_time *time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81878d00)
Location: drivers/rtc/rtc-mc146818-lib.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81878d00-ffffffff81878eb0: mc146818_get_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
