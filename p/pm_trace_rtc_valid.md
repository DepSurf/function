# Function: <code>pm_trace_rtc_valid</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: include/linux/pm-trace.h:11
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/pm-trace.h:11
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: include/linux/pm-trace.h:11
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/pm-trace.h:11
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: include/linux/pm-trace.h:12
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (0)
Location: include/linux/pm-trace.h:12
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038da5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d1acb)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81039fb5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f8c1d)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103c585)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81839839)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cd45)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186b1a9)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fbc5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193ee45)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fa45)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819449a9)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810413e5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819281eb)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81047665)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cbb33)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81050535)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2ba45)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105da41)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cbf8b5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105f091)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d27215)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_read_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81066141)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81ddd015)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_read_time
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cec5)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181de59)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8102c555)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e5509)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cd05)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185f339)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103dd95)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a1b9)
Location: include/linux/pm-trace.h:12
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
</details>
</li>
</ul>

## Differences
