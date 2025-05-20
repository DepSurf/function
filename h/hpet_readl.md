# Function: <code>hpet_readl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061de6)
Location: arch/x86/kernel/hpet.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
**Symbols:**

```
ffffffff81062e00-ffffffff81062e11: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106253e)
Location: arch/x86/kernel/hpet.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81062a90-ffffffff81062aa1: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810655ae)
Location: arch/x86/kernel/hpet.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81065c20-ffffffff81065c31: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810644e7)
Location: arch/x86/kernel/hpet.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81064cf0-ffffffff81064d01: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068667)
Location: arch/x86/kernel/hpet.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81068e80-ffffffff81068e91: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b1c1)
Location: arch/x86/kernel/hpet.c:63
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8106b920-ffffffff8106b931: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070f51)
Location: arch/x86/kernel/hpet.c:59
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_read
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810716b0-ffffffff810716c1: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074ed4)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81075530-ffffffff8107553c: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075ea4)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81076500-ffffffff8107650c: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107cdf0)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8107d7c0-ffffffff8107d7cc: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107cccb)
Location: arch/x86/kernel/hpet.c:76
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8107d730-ffffffff8107d73c: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107dde9)
Location: arch/x86/kernel/hpet.c:76
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8107e860-ffffffff8107e86c: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108c759)
Location: arch/x86/kernel/hpet.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8108d4e0-ffffffff8108d4ec: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109d141)
Location: arch/x86/kernel/hpet.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff8109e040-ffffffff8109e052: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b41e1)
Location: arch/x86/kernel/hpet.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810b52a0-ffffffff810b52b2: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b72e1)
Location: arch/x86/kernel/hpet.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810b8370-ffffffff810b8382: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810be721)
Location: arch/x86/kernel/hpet.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810bf7b0-ffffffff810bf7c2: hpet_readl (STB_GLOBAL)
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
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074ea4)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81075500-ffffffff8107550c: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064ed4)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810654f0-ffffffff810654fc: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074e54)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff810754b0-ffffffff810754bc: hpet_readl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int hpet_readl(unsigned int a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076eb4)
Location: arch/x86/kernel/hpet.c:75
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
  - arch/x86/kernel/hpet.c:_hpet_print_config
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
**Symbols:**

```
ffffffff81077510-ffffffff8107751c: hpet_readl (STB_GLOBAL)
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
