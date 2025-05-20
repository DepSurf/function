# Function: <code>__clocksource_register_scale</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810f7e20)
Location: kernel/time/clocksource.c:728
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - kernel/time/jiffies.c:register_refined_jiffies
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810f7e20-ffffffff810f7ff4: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810ff150)
Location: kernel/time/clocksource.c:760
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810ff150-ffffffff810ff254: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81101fc0)
Location: kernel/time/clocksource.c:770
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff81101fc0-ffffffff811020c4: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81104130)
Location: kernel/time/clocksource.c:777
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff81104130-ffffffff81104239: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110f1b0)
Location: kernel/time/clocksource.c:776
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff8110f1b0-ffffffff8110f2b9: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8111ab80)
Location: kernel/time/clocksource.c:798
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff8111ab80-ffffffff8111ac9c: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81126450)
Location: kernel/time/clocksource.c:918
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff81126450-ffffffff81126584: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81130e70)
Location: kernel/time/clocksource.c:918
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81130e70-ffffffff81130fbf: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113cdb0)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff8113cdb0-ffffffff8113ceff: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
```
**Symbols:**

```
ffffffff8114cafb-ffffffff8114cb2c: __clocksource_register_scale.cold (STB_LOCAL)
ffffffff8114c3a0-ffffffff8114c517: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:917
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81be3a32-ffffffff81be3a63: __clocksource_register_scale.cold (STB_LOCAL)
ffffffff81148800-ffffffff81148977: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1018
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81bd5951-ffffffff81bd5982: __clocksource_register_scale.cold (STB_LOCAL)
ffffffff81149cf0-ffffffff81149e80: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1150
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81cb181c-ffffffff81cb184d: __clocksource_register_scale.cold (STB_LOCAL)
ffffffff8116d5c0-ffffffff8116d750: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:1156
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81e62dc9-ffffffff81e62df8: __clocksource_register_scale.cold (STB_LOCAL)
ffffffff811a1690-ffffffff811a1835: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811e03b0)
Location: kernel/time/clocksource.c:1175
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff811e03b0-ffffffff811e057b: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f48b0)
Location: kernel/time/clocksource.c:1186
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff811f48b0-ffffffff811f4a7b: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120a9f0)
Location: kernel/time/clocksource.c:1209
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff8120a9f0-ffffffff8120abbb: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a6ea8)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/mmio.c:clocksource_mmio_init
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
```
**Symbols:**

```
ffff8000101a6ea8-ffff8000101a6f90: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f2550)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/clocksource/mmio.c:clocksource_mmio_init
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_register
  - drivers/clocksource/timer-tegra.c:tegra20_init_rtc
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init
  - drivers/clocksource/timer-rda.c:rda_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
**Symbols:**

```
c03f2550-c03f2620: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c0000000002097c0)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/powerpc/kernel/time.c:time_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
```
**Symbols:**

```
c0000000002097c0-c0000000002098d0: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe000132f4c)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/timer-riscv.c:riscv_timer_init_dt
```
**Symbols:**

```
ffffffe000132f4c-ffffffe00013301e: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81135560)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81135560-ffffffff811356af: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81127fc0)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81127fc0-ffffffff8112810f: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81133280)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff81133280-ffffffff811333cf: __clocksource_register_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource *cs, u32 scale, u32 freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113fca0)
Location: kernel/time/clocksource.c:925
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/time/jiffies.c:register_refined_jiffies
  - kernel/time/jiffies.c:init_jiffies_clocksource
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
**Symbols:**

```
ffffffff8113fca0-ffffffff8113fdef: __clocksource_register_scale (STB_GLOBAL)
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
