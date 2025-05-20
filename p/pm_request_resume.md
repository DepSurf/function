# Function: <code>pm_request_resume</code>

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
In block/elevator.c (ffffffff813b41a8)
Location: include/linux/pm_runtime.h:211
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff81433f1e)
Location: include/linux/pm_runtime.h:211
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b888)
Location: include/linux/pm_runtime.h:211
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/base/power/generic_ops.c (ffffffff81554912)
Location: include/linux/pm_runtime.h:211
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff8161ed76)
Location: include/linux/pm_runtime.h:211
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/elevator.c (ffffffff813f7ea3)
Location: include/linux/pm_runtime.h:217
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff81482c1c)
Location: include/linux/pm_runtime.h:217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff81497ffd)
Location: include/linux/pm_runtime.h:217
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/base/power/generic_ops.c (ffffffff815a6912)
Location: include/linux/pm_runtime.h:217
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff8167f5d2)
Location: include/linux/pm_runtime.h:217
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/elevator.c (ffffffff814118ce)
Location: include/linux/pm_runtime.h:220
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff814a41ac)
Location: include/linux/pm_runtime.h:220
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff814a69a6)
Location: include/linux/pm_runtime.h:220
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff814b98ad)
Location: include/linux/pm_runtime.h:220
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/base/power/generic_ops.c (ffffffff815d50d2)
Location: include/linux/pm_runtime.h:220
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff816ad30f)
Location: include/linux/pm_runtime.h:220
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/elevator.c (ffffffff8141f46a)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff814ae1ec)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff814b0986)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff814c408b)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff814cfe9e)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff814f9f9f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/generic_ops.c (ffffffff815e9b92)
Location: include/linux/pm_runtime.h:208
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff816c24ca)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727181)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_complete
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
In block/elevator.c (ffffffff81449f61)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff814ed5cc)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff814eff5f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff815042c7)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815100ee)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff8153baff)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/usb/core/port.c (ffffffff8172e29a)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817987e1)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_complete
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
In block/elevator.c (ffffffff8147cce3)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In drivers/pci/pci.c (ffffffff8151d1df)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff81520b1f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff81535263)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815451de)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff8157194f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/usb/core/port.c (ffffffff8176d345)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db543)
Location: include/linux/pm_runtime.h:208
Inline: True
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
In block/blk-core.c (ffffffff8149e9ce)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff815328df)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff8153694f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff8154124e)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c813)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff8158971f)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/usb/core/port.c (ffffffff81791995)
Location: include/linux/pm_runtime.h:208
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818028f3)
Location: include/linux/pm_runtime.h:208
Inline: True
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
In block/blk-core.c (ffffffff814ccb73)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff8156201b)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff81566232)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff81570ba8)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c44d)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815ba260)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815caeec)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff817d09c9)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843db3)
Location: include/linux/pm_runtime.h:209
Inline: True
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
In block/blk-core.c (ffffffff814e5daa)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff815831bb)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff81587592)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff81591d98)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8159dead)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815db4a0)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815ec16c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff818018e4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875723)
Location: include/linux/pm_runtime.h:209
Inline: True
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
In block/blk-core.c (ffffffff81544e52)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff81629d9b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff8162d392)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d94f)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816405a8)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff816858b0)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff81697d2c)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff818d2214)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a243)
Location: include/linux/pm_runtime.h:219
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
In block/blk-core.c (ffffffff815613d6)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff816501cb)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff81652a82)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff81663fdf)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816669b8)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff816a36c0)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff816b4e5c)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff818dc5f4)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fdd3)
Location: include/linux/pm_runtime.h:344
Inline: True
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
In block/blk-core.c (ffffffff81569b26)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff81632d8b)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff81635542)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff8164644f)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81648e68)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff816864c0)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff81696f04)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff818bf7d6)
Location: include/linux/pm_runtime.h:344
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933c93)
Location: include/linux/pm_runtime.h:344
Inline: True
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
In block/blk-core.c (ffffffff815cd47f)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff816a2efb)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff816a5452)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7cbf)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba8b8)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff816fb7d0)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff8170cdaa)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff81955e46)
Location: include/linux/pm_runtime.h:351
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7093)
Location: include/linux/pm_runtime.h:351
Inline: True
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
In block/blk-core.c (ffffffff81678a07)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff817c50c2)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff817c7ac6)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc0be)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff817df19e)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff81828c8f)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff8183b56a)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff81aaf0a1)
Location: include/linux/pm_runtime.h:380
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39bab)
Location: include/linux/pm_runtime.h:380
Inline: True
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
In block/blk-core.c (ffffffff81734e7b)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff818e2142)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff818e5236)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff818fdf22)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81901efe)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff8195ad9f)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff81970cdd)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c36ba0)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffffffff817713db)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff81925582)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff81928876)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff819413d4)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff819454b7)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff819a126f)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff819b736d)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff81c9de90)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffffffff817b371b)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff8196dccf)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
```
```
In drivers/pci/pci-driver.c (ffffffff81971096)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a634)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff8198e7e7)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff819e991f)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff81a0191d)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/scsi/sd.c (ffffffff81c40655)
Location: include/linux/pm_runtime.h:382
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff81d52a40)
Location: include/linux/pm_runtime.h:382
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffff8000105e3364)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffff8000106e7004)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffff8000106eb23c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffff8000106f7c00)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffff800010706344)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffff8000107674d0)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffff80001077788c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffff800010a35d5c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba520)
Location: include/linux/pm_runtime.h:209
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
In block/blk-core.c (c0790680)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (c0882244)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (c0886d0c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pcie/pme.c (c089d330)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/usb/core/port.c (c0b08ac4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99ba8)
Location: include/linux/pm_runtime.h:209
Inline: True
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
In block/blk-core.c (c000000000776c10)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (c000000000861648)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (c00000000086694c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/usb/core/port.c (c000000000af31c4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dbc8)
Location: include/linux/pm_runtime.h:209
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
In block/blk-core.c (ffffffe000424f4e)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffe0004bd79a)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_wakeup
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3fde)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/usb/core/port.c (ffffffe000652baa)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffffffff814de38a)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff815776db)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pm_runtime.h:209
Inline: True
```
```
In drivers/pci/pci-acpi.c (ffffffff81585c28)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff815916ad)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815cdc80)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815db4df)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff817b9cc4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffffffff814ced2a)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff81565e3b)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff8156a1f2)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff815749f8)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff815809a1)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815b77f0)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815c6b1f)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff817ab6f4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
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
In block/blk-core.c (ffffffff814da41a)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff81576f0b)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff8157b2e2)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff81585ae8)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff81591bfd)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815cf780)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815e044c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff817f6764)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186abd3)
Location: include/linux/pm_runtime.h:209
Inline: True
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
In block/blk-core.c (ffffffff814f3095)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In drivers/pci/pci.c (ffffffff815913eb)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-driver.c (ffffffff815958f2)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/pci/pci-acpi.c (ffffffff8159ff98)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac270)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/acpi/device_pm.c (ffffffff815e9640)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/acpi/power.c (ffffffff815fa30c)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/usb/core/port.c (ffffffff818109a4)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884b63)
Location: include/linux/pm_runtime.h:209
Inline: True
```
</details>
</li>
</ul>

## Differences
