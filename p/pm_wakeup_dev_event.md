# Function: <code>pm_wakeup_dev_event</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1eb0)
Location: drivers/base/power/wakeup.c:793
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff815f1eb0-ffffffff815f1f12: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659460)
Location: drivers/base/power/wakeup.c:794
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff81659460-ffffffff816594c2: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695150)
Location: drivers/base/power/wakeup.c:793
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff81695150-ffffffff816951b1: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b57f0)
Location: drivers/base/power/wakeup.c:799
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff816b57f0-ffffffff816b5851: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef390)
Location: drivers/base/power/wakeup.c:783
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff816ef390-ffffffff816ef3f1: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817134f0)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff817134f0-ffffffff81713551: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf330)
Location: drivers/base/power/wakeup.c:862
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:report_wakeup_requests
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff817cf330-ffffffff817cf391: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3930)
Location: drivers/base/power/wakeup.c:862
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:report_wakeup_requests
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff817e3930-ffffffff817e3991: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7b00)
Location: drivers/base/power/wakeup.c:863
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff817c7b00-ffffffff817c7b61: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851ec0)
Location: drivers/base/power/wakeup.c:864
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff81851ec0-ffffffff81851f21: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997ec0)
Location: drivers/base/power/wakeup.c:864
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff81997ec0-ffffffff81997f39: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08fe0)
Location: drivers/base/power/wakeup.c:834
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff81b08fe0-ffffffff81b09059: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b57000)
Location: drivers/base/power/wakeup.c:829
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff81b57000-ffffffff81b57079: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf5f0)
Location: drivers/base/power/wakeup.c:829
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/sleep.c:acpi_pm_finish
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff81baf5f0-ffffffff81baf669: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff8000109046c8)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffff8000109046c8-ffff800010904794: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee518)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - sound/soc/soc-jack.c:gpio_handler
```
**Symbols:**

```
c09ee518-c09ee578: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2f00)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c0000000009a2f00-c0000000009a2f9c: pm_wakeup_dev_event (STB_GLOBAL)
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
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:181
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9860)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff816d9860-ffffffff816d98c1: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3eb0)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
```
**Symbols:**

```
ffffffff816b3eb0-ffffffff816b3f11: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817071b0)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff817071b0-ffffffff81707211: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pm_wakeup_dev_event(struct device *dev, unsigned int msec, bool hard);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721c00)
Location: drivers/base/power/wakeup.c:803
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
  - drivers/base/power/main.c:__device_suspend
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/mmc/core/core.c:_mmc_detect_change
```
**Symbols:**

```
ffffffff81721c00-ffffffff81721c61: pm_wakeup_dev_event (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
