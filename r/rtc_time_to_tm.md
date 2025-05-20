# Function: <code>rtc_time_to_tm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038821)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8167620a)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037a7a)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816d6e5e)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103783a)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff81706b3e)
Location: include/linux/rtc.h:38
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
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
In arch/x86/kernel/rtc.c (ffffffff810358ea)
Location: include/linux/rtc.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c720)
Location: include/linux/rtc.h:36
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037c0a)
Location: include/linux/rtc.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-sun6i.c (ffff800010aadc38)
Location: include/linux/rtc.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-pl031.c (c0b8d874)
Location: include/linux/rtc.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_read_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time
```
</details>
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
