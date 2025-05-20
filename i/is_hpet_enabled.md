# Function: <code>is_hpet_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061fe5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff810620f0-ffffffff81062100: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061ef5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81061f20-ffffffff81061f30: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064f85)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81064fb0-ffffffff81064fc0: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81063ee5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81063c80-ffffffff81063ca7: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068065)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81067e00-ffffffff81067e27: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106acf5)
Location: arch/x86/kernel/hpet.c:134
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8106aa40-ffffffff8106aa67: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070a85)
Location: arch/x86/kernel/hpet.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff810707d0-ffffffff810707f7: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074a15)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81074810-ffffffff81074837: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810759e5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff810757e0-ffffffff81075807: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d535)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8107c9d0-ffffffff8107c9f7: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d4a5)
Location: arch/x86/kernel/hpet.c:134
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8107c7e0-ffffffff8107c807: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e415)
Location: arch/x86/kernel/hpet.c:134
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8107d990-ffffffff8107d9b7: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108cf55)
Location: arch/x86/kernel/hpet.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81c9edbe-ffffffff81c9eded: is_hpet_enabled.cold (STB_LOCAL)
ffffffff8108ce30-ffffffff8108ce77: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109dbc5)
Location: arch/x86/kernel/hpet.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81e4e20c-ffffffff81e4e23b: is_hpet_enabled.cold (STB_LOCAL)
ffffffff8109da80-ffffffff8109dacf: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4da5)
Location: arch/x86/kernel/hpet.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff82054201-ffffffff82054230: is_hpet_enabled.cold (STB_LOCAL)
ffffffff810b4c40-ffffffff810b4c8f: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7e75)
Location: arch/x86/kernel/hpet.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff820d27c2-ffffffff820d27f1: is_hpet_enabled.cold (STB_LOCAL)
ffffffff810b7d10-ffffffff810b7d5f: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bf2b5)
Location: arch/x86/kernel/hpet.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_register_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff821ad628-ffffffff821ad657: is_hpet_enabled.cold (STB_LOCAL)
ffffffff810bf150-ffffffff810bf19f: is_hpet_enabled (STB_GLOBAL)
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
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810749e5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff810747e0-ffffffff81074807: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064a15)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81064810-ffffffff81064837: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074995)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81074790-ffffffff810747b7: is_hpet_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int is_hpet_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810769f5)
Location: arch/x86/kernel/hpet.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_dropped_irq
  - arch/x86/kernel/hpet.c:hpet_set_alarm_time
  - arch/x86/kernel/hpet.c:hpet_set_rtc_irq_bit
  - arch/x86/kernel/hpet.c:hpet_unregister_irq_handler
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff810767f0-ffffffff81076817: is_hpet_enabled (STB_GLOBAL)
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
