# Function: <code>dwc2_read_hprt0</code>

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
In drivers/usb/dwc2/core.c (ffffffff8162214a)
Location: drivers/usb/dwc2/hcd.h:396
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626946)
Location: drivers/usb/dwc2/hcd.h:396
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8168ab0a)
Location: drivers/usb/dwc2/hcd.h:466
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816b8c22)
Location: drivers/usb/dwc2/hcd.h:466
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816ccf64)
Location: drivers/usb/dwc2/hcd.h:466
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8173955a)
Location: drivers/usb/dwc2/hcd.h:467
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81779615)
Location: drivers/usb/dwc2/hcd.h:488
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8179f3f6)
Location: drivers/usb/dwc2/hcd.h:488
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff817ddf66)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180eeb6)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dfbb6)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e9a16)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff818c43b5)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cc74b)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff8195beb2)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966355)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff81ab5bed)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0511)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff81c3e4b2)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c49fc1)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff81ca5948)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb15c1)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/core_intr.c (ffffffff81d5a598)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d662d1)
Location: drivers/usb/dwc2/hcd.h:462
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffff800010a479d4)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (c0b1a15c)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (c000000000b0c6dc)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffe0006644bc)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
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
In drivers/usb/dwc2/hcd.c (ffffffff817c7296)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81803d36)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181de46)
Location: drivers/usb/dwc2/hcd.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
</details>
</li>
</ul>

## Differences
