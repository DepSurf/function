# Function: <code>rtc_cmos_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810387d0)
Location: arch/x86/kernel/rtc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff810387d0-ffffffff810387e1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037b38)
Location: arch/x86/kernel/rtc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81037a30-ffffffff81037a41: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037911)
Location: arch/x86/kernel/rtc.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff810377f0-ffffffff81037801: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810359c1)
Location: arch/x86/kernel/rtc.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff810358a0-ffffffff810358b1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037ce1)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81037bc0-ffffffff81037bd1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038de1)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81038cf0-ffffffff81038d01: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81039ff1)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81039f00-ffffffff81039f11: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103c5cf)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103c4c0-ffffffff8103c4d1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cd8f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103cc80-ffffffff8103cc91: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fc0f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103fb10-ffffffff8103fb21: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fa8f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103f990-ffffffff8103f9a1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8104142f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81041330-ffffffff81041341: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810476be)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff810475b0-ffffffff810475c1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810505a2)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
```
**Symbols:**

```
ffffffff81050450-ffffffff81050467: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105d8b0)
Location: arch/x86/kernel/rtc.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
```
**Symbols:**

```
ffffffff8105d8b0-ffffffff8105d8c7: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105ef00)
Location: arch/x86/kernel/rtc.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
```
**Symbols:**

```
ffffffff8105ef00-ffffffff8105ef17: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81065fb0)
Location: arch/x86/kernel/rtc.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time_callback
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm_callback
```
**Symbols:**

```
ffffffff81065fb0-ffffffff81065fc7: rtc_cmos_read (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cf0f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103ce00-ffffffff8103ce11: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8102c59f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8102c490-ffffffff8102c4a1: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cd4f)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103cc40-ffffffff8103cc51: rtc_cmos_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned char rtc_cmos_read(unsigned char addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103dddf)
Location: arch/x86/kernel/rtc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
Direct callers:
  - arch/x86/kernel/bootflag.c:sbf_init
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_nvram_read
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff8103dcd0-ffffffff8103dce1: rtc_cmos_read (STB_GLOBAL)
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
