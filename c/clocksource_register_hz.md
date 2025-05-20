# Function: <code>clocksource_register_hz</code>

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
In arch/x86/xen/time.c (ffffffff81f6394e)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f6d8ae)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/hpet.c (ffffffff81f7412b)
Location: include/linux/clocksource.h:213
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81f748be)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81fb73e5)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff81fb7578)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff81f8b520)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95c6a)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/hpet.c (ffffffff81f9c981)
Location: include/linux/clocksource.h:213
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81f9d0ea)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff81fe4ebf)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff81fe5059)
Location: include/linux/clocksource.h:213
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff81fc6903)
Location: include/linux/clocksource.h:216
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102be53)
Location: include/linux/clocksource.h:216
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/hpet.c (ffffffff81fd7ecc)
Location: include/linux/clocksource.h:216
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81fd8679)
Location: include/linux/clocksource.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff82023854)
Location: include/linux/clocksource.h:216
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff820239ee)
Location: include/linux/clocksource.h:216
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff820a3825)
Location: include/linux/clocksource.h:220
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a156)
Location: include/linux/clocksource.h:220
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/hpet.c (ffffffff820b8d09)
Location: include/linux/clocksource.h:220
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff820b9489)
Location: include/linux/clocksource.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff821065e4)
Location: include/linux/clocksource.h:220
Inline: True
```
```
In drivers/clocksource/numachip.c (ffffffff8210672c)
Location: include/linux/clocksource.h:220
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff826a9d0f)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a3d9)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/hpet.c (ffffffff826bf553)
Location: include/linux/clocksource.h:221
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff826bfdf7)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8270fcef)
Location: include/linux/clocksource.h:221
Inline: True
```
```
In drivers/clocksource/numachip.c (ffffffff8270fe85)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff826d2e75)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff826d89d2)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/hpet.c (ffffffff826e932f)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff826e9d04)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff82739f21)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff8273a11e)
Location: include/linux/clocksource.h:221
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff82888f05)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288ec68)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/hpet.c (ffffffff8289feeb)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a0969)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff828f3ef0)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff828f40ed)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/xen/time.c (ffffffff828a01ae)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828b7f25)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828b8b6e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8290f91e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff8290fb1c)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8290fbef)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff828a329e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828be423)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bf05c)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9e5e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff829195f9)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff829197f7)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8291990e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff82cc968d)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff82ce29bc)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82ce334c)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec7aa)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff82d2bd15)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff82d2bf10)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82d2c034)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
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
In arch/x86/xen/time.c (ffffffff82fb54de)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcfc59)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82fd0645)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8e04)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8301a6dd)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff8301a8d8)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a9eb)
Location: include/linux/clocksource.h:235
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff831bfcb1)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff831da754)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff831db2c7)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e3681)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8322572b)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff83225926)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83225a01)
Location: include/linux/clocksource.h:241
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff832a03b0)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd941)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff832be63c)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c70c6)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8330f8a0)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff8330fae7)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fbdb)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff8344f275)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f331)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83470365)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479ece)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff834c966d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff834c990a)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff834c9a10)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff83e6abaa)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff83e95945)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96e0c)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea449d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff83f0acc1)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff83f0b003)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b107)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff8368b54d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff836b94c6)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba9bc)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c881d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff83730e81)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff837311d3)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff837312d7)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff838bb10d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9deb)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb3c2)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f941d)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff83965411)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff83965773)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83965877)
Location: include/linux/clocksource.h:244
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (ffff800010b64808)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b657ac)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/mmio.c (ffff8000114a8264)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_init
```
```
In drivers/clocksource/timer-sprd.c (ffff8000114a8bc4)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a90cc)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/timer.c (c151305c)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
```
```
In drivers/clocksource/sh_cmt.c (c0c452d0)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c4674c)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/em_sti.c (c0c47060)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_probe
```
```
In drivers/clocksource/mmio.c (c15aab90)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_init
```
```
In drivers/clocksource/dw_apb_timer.c (c0c49034)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_register
```
```
In drivers/clocksource/timer-tegra.c (c15abfc4)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra20_init_rtc
```
```
In drivers/clocksource/exynos_mct.c (c15ac298)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/clocksource/timer-qcom.c (c15ac614)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
```
```
In drivers/clocksource/timer-ti-32k.c (c15ac94c)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init
```
```
In drivers/clocksource/timer-rda.c (c15acd24)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-rda.c:rda_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15acfb4)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
```
```
In drivers/clocksource/arm_global_timer.c (c15ada44)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c000000001348eb4)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:time_init
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
In drivers/clocksource/timer-riscv.c (ffffffe00003a5ce)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-riscv.c:riscv_timer_init_dt
```
</details>
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
In arch/x86/xen/time.c (ffffffff8289129e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828a93f9)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828aa032)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff828fe765)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff828fe963)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828fea7a)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/kernel/hpet.c (ffffffff828a14a5)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a2313)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff828f629b)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff828f6499)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f65df)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff828a429e)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc2f8)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bcf31)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In drivers/clocksource/acpi_pm.c (ffffffff82913994)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff82913b92)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82913ca9)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
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
In arch/x86/xen/time.c (ffffffff828a42b2)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf450)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828c0081)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828cae9b)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
```
In drivers/clocksource/acpi_pm.c (ffffffff8291a65b)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
```
In drivers/clocksource/numachip.c (ffffffff8291a859)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8291a970)
Location: include/linux/clocksource.h:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
</details>
</li>
</ul>

## Differences
