# Function: <code>pm_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_wakeup_event(struct device *dev, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c360)
Location: drivers/base/power/wakeup.c:794
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff8155c360-ffffffff8155c3b1: pm_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_wakeup_event(struct device *dev, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae560)
Location: drivers/base/power/wakeup.c:792
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff815ae560-ffffffff815ae5b1: pm_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_wakeup_event(struct device *dev, unsigned int msec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd360)
Location: drivers/base/power/wakeup.c:792
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff815dd360-ffffffff815dd3b1: pm_wakeup_event (STB_GLOBAL)
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
In drivers/pci/pci.c (ffffffff814ae1dd)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff814c4078)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff814cfe8f)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff814f8737)
Location: include/linux/pm_wakeup.h:211
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814f9f93)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff815ed933)
Location: include/linux/pm_wakeup.h:211
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815eef9e)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff816ab170)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
```
```
In drivers/mmc/core/core.c (ffffffff81770fca)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff814ed5bd)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff815042b4)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815100df)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81539a37)
Location: include/linux/pm_wakeup.h:211
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff8153baf3)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff81654ce3)
Location: include/linux/pm_wakeup.h:211
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8165634e)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817165c0)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
```
```
In drivers/mmc/core/core.c (ffffffff817e6d2a)
Location: include/linux/pm_wakeup.h:211
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff8151d1d0)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff81535250)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815451cf)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff8157018f)
Location: include/linux/pm_wakeup.h:218
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff81571943)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff816905b3)
Location: include/linux/pm_wakeup.h:218
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816920a2)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817553d5)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817595eb)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/mmc/core/core.c (ffffffff8183008a)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff815328d0)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8154123f)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c800)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff81587d4f)
Location: include/linux/pm_wakeup.h:218
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff81589713)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0dc3)
Location: include/linux/pm_wakeup.h:218
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b2709)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817791a1)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff8177db5b)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/serio/i8042.c (ffffffff817e1b68)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff8185c30a)
Location: include/linux/pm_wakeup.h:218
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff8156200c)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81570b99)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c43d)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815b89be)
Location: include/linux/pm_wakeup.h:196
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815ba254)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff816eaa77)
Location: include/linux/pm_wakeup.h:196
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816ec45d)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817b7011)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817bbe9b)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182dd93)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff8189ff3a)
Location: include/linux/pm_wakeup.h:196
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff815831ac)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81591d89)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8159de9d)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815d9bfc)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815db494)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff8170eab7)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817104cd)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817e7731)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817ec69b)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f6c3)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff818d579a)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In kernel/time/alarmtimer.c (ffffffff8114f482)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff81629d8c)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d940)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816405cf)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81683e23)
Location: include/linux/pm_wakeup.h:200
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff816858a4)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca22a)
Location: include/linux/pm_wakeup.h:200
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818b37c6)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:report_wakeup_requests
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff818bc09b)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819336e3)
Location: include/linux/pm_wakeup.h:200
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff819a6b75)
Location: include/linux/pm_wakeup.h:200
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff8114b677)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff816501bc)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff81663fd0)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816669df)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81c00d92)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff816a36b4)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff817decca)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818c2136)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:report_wakeup_requests
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff818c910b)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193a933)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In kernel/time/alarmtimer.c (ffffffff8114cb27)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff81632d7c)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff81646440)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81648e8f)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81bf27e5)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff816864b4)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff817c30ca)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818a6b92)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff818ac59b)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191da33)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In kernel/time/alarmtimer.c (ffffffff81170ac7)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff816a2eec)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7cb0)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba8df)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81cef0c9)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_pm.c (ffffffff816fb7c4)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d51a)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193ba1f)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff819415eb)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c0f10)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In kernel/time/alarmtimer.c (ffffffff811a50cf)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff817c50b3)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc0af)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff817df1d0)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff81eb6855)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_pm.c (ffffffff81828c83)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff81992904)
Location: include/linux/pm_wakeup.h:210
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a93713)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff81a99807)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1f828)
Location: include/linux/pm_wakeup.h:210
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In kernel/time/alarmtimer.c (ffffffff811e49df)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff818e2133)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff818fdf13)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81901f30)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff819583f4)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_pm.c (ffffffff8195ad93)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff81b02df0)
Location: include/linux/pm_wakeup.h:202
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c15943)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d5c7)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb1a88)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In kernel/time/alarmtimer.c (ffffffff811f903f)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff81925573)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff819413c5)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff819454a8)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff8199e8d4)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_pm.c (ffffffff819a1263)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acbbc5)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
```
In drivers/base/power/wakeirq.c (ffffffff81b50df0)
Location: include/linux/pm_wakeup.h:202
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c7c750)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff81c844b7)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d190e4)
Location: include/linux/pm_wakeup.h:202
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
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
In kernel/time/alarmtimer.c (ffffffff8120f21a)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/pci/pci.c (ffffffff8196dcc7)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a625)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff8198e7d8)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/sleep.c (ffffffff819e6f74)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_pm.c (ffffffff819e9913)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e369)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9370)
Location: include/linux/pm_wakeup.h:212
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d313a0)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff81d38eb7)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcee04)
Location: include/linux/pm_wakeup.h:212
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
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
In drivers/pci/pci.c (ffff8000106e6ff4)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffff8000106f7bf0)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffff800010706334)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffff8000107674c0)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffff8000108feae4)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffff800010900c74)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffff800010a16750)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffff800010a1cdb8)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa1988)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffff800010b2f3cc)
Location: include/linux/pm_wakeup.h:191
Inline: True
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
In drivers/pci/pci.c (c0882234)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (c089d328)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/base/power/wakeirq.c (c09e8f74)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (c09eaef0)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (c0aeea44)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (c0af3778)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (c0b818c8)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (c0c0a728)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In sound/soc/soc-jack.c (c0cad3c4)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:gpio_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861634)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/base/power/wakeirq.c (c00000000099ba80)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (c00000000099e56c)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (c000000000acf11c)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (c000000000ad50a0)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82494)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (c000000000c28e64)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:191
Inline: True
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
In drivers/pci/pci.c (ffffffff815776cc)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81585c19)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8159169d)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815cc3ef)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815cdc74)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff816d4207)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d66f5)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff8179fb11)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817a4a7b)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818146d3)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff8187915a)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff81565e2c)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff815749e9)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff81580991)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815b5f56)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815b77e4)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff816af4a7)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b0ebd)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff81791791)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817965bb)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dbe03)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
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
In drivers/pci/pci.c (ffffffff81576efc)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81585ad9)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff81591bed)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815cdedc)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815cf774)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff81702777)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8170418d)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817dc5b1)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817e151b)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853853)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff818ca5fa)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff815913dc)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8159ff89)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac260)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/sleep.c (ffffffff815e7d9c)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815e9634)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff8171cf97)
Location: include/linux/pm_wakeup.h:191
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171e28d)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/usb/core/hub.c (ffffffff817f6841)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffffffff817fb90b)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186ec23)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff818e711a)
Location: include/linux/pm_wakeup.h:191
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
</ul>
