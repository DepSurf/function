# Function: <code>div_sc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f713d5)
Location: include/linux/clockchips.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f99b9a)
Location: include/linux/clockchips.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5076)
Location: include/linux/clockchips.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b5d6e)
Location: include/linux/clockchips.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff826bc578)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e6320)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289ce63)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b495a)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
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
In arch/x86/kernel/apic/apic.c (ffffffff828b7db3)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9efb)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff82cdcecd)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec847)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff82fc9261)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8ea1)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff831d3ba2)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e371e)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff832b671e)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c715a)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff834681cd)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479f62)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff83e8c586)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea4542)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff836afda6)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c88c2)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff838e0306)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f94c2)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
</details>
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
In drivers/clocksource/sh_cmt.c (ffff800010b646e4)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
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
In drivers/clocksource/sh_cmt.c (c0c44cd4)
Location: include/linux/clockchips.h:172
Inline: True
Direct callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
**Symbols:**

```
c0c44cd4-c0c44d30: div_sc.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a5dba)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289defc)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8cca)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
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
In arch/x86/kernel/apic/apic.c (ffffffff828b8dcb)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_init_clockevent
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828caf38)
Location: include/linux/clockchips.h:172
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
</details>
</li>
</ul>

## Differences
