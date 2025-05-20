# Function: <code>device_may_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool device_may_wakeup(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810faffa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff81433556)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_target_state
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b60e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/pci/pci-acpi.c (ffffffff814574fc)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff8147b59a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff8147caf2)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
```
```
In drivers/acpi/proc.c (ffffffff8147dbc4)
Location: include/linux/pm_wakeup.h:86
Inline: False
Direct callers:
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff814bbbdf)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81503a95)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff8155828d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81558785)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:pm_dev_dbg
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157a105)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff8158e86a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8158ed35)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8158f1fa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81590135)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81590a25)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8997.c:max8997_resume
```
```
In drivers/mfd/max8998.c (ffffffff81591605)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/max8998.c:max8998_resume
```
```
In drivers/mfd/sec-core.c (ffffffff81595b9a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/mdio_bus.c (ffffffff815ec977)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/mdio_bus.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8160ec18)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff81615223)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816202c7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d065)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8164355d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81643f35)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81648379)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81665919)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8167738d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/power/charger-manager.c (ffffffff81680237)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_noirq
```
**Symbols:**

```
ffffffff8147dbc4-ffffffff8147dbe5: device_may_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool device_may_wakeup(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811022fa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8147eeb8)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_target_state
```
```
In drivers/pci/pcie/pme.c (ffffffff814978eb)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4115)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff814c9c28)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff814cbadf)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff814cc367)
Location: include/linux/pm_wakeup.h:86
Inline: False
Direct callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8150b64b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
```
```
In drivers/tty/serial/serial_core.c (ffffffff815550b5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff815aa3dd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff815ad586)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff815af9c7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cf165)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff815e371a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff815e3be5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff815e40aa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e4fb5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff815e589a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff815e644d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff815ea9aa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff816498d7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8166e818)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff816751e3)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680d57)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169dc75)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a4030)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a49f5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8e7e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff816c5b8e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d80a1)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/charger-manager.c (ffffffff816e1077)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_noirq
```
**Symbols:**

```
ffffffff814cc367-ffffffff814cc386: device_may_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool device_may_wakeup(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81104b0a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff814a05a4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_target_state
```
```
In drivers/pci/pcie/pme.c (ffffffff814b926b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff814c5ea5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff814ebb6c)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff814eda0d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff814ee295)
Location: include/linux/pm_wakeup.h:86
Inline: False
Direct callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8152f86b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
```
```
In drivers/tty/serial/serial_core.c (ffffffff81581d79)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff815d908d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff815dc346)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff815de6c5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fbda5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff816105ca)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81610a95)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81610f5a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611e65)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff8161274a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff816132fd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff816177ba)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff8167abb7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8169c4f8)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff816a2e73)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816aea87)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cbdb5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d2130)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2af5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d6f9e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff816f3bae)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817007f7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8170844c)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff817114e7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
```
**Symbols:**

```
ffffffff814ee295-ffffffff814ee2b4: device_may_wakeup (STB_LOCAL)
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
In kernel/time/alarmtimer.c (ffffffff81106bfa)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff814aa254)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3a3b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff814cff15)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff814f7edb)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff814f9eed)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff814fb34a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8154291e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff815961c9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff815edbad)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff815f0ec2)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff815f3246)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8160fb85)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff8162466d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81624b45)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81624ffd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625ed5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff816267ea)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff8162735d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8162b6cd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff8168fbc9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff816b1902)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff816b804a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c3751)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e04e5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e679d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7195)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb242)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff817096fe)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8171605a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171e071)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff817298d7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff81111cb9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff814e94b4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff814f096a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff81503c7b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8151015e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff8153928b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff8153b790)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff8153cf9a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154a6bb)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815a5a3d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff815fada9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81654f5d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff8165833b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff8165a9fb)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81678405)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff8168cf5d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8168d435)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8168d8ed)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e7c5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff8168f0ba)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff8168fc2d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8169400d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff816f98c9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8171cf3a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff8172393c)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172f531)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174cd05)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81752fcd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817539d5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81757a32)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff8177a8ae)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8178725a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178f2f4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179b067)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8111d6a3)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff81518c44)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff815202a9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff81534f8b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81545264)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff8156f0fd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815715d0)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff81572e3a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815809eb)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815dd63e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81632ec9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff8168b4bc)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff8169086d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81691ef0)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff81696641)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b3e95)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff816c9064)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff816c9535)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff816c99f4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ca985)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff816cb1d1)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff816cbd44)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff816d0164)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff81736ee7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8175b9c7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff8176258b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff8176d0e5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176eabd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d653)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817936ec)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794143)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81799a45)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff817bb13e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c832a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d1b5e)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e25b5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff81128e53)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8152e6b4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff815360d7)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff815412da)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c19b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff81586cbd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff8158939a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff8158aa4a)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598f5b)
Location: include/linux/pm_wakeup.h:86
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815f6dde)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81651fc9)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff816ab6ec)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0ecd)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff816b2557)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff816b6d11)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d50f5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff816ea5e4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff816eaab5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff816eaf74)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebe45)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff816ec714)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff816ed2f4)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff816f1784)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a092)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff8177fef6)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff81786b9b)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81791735)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8179313d)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b3dc3)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b9cbc)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba713)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bf6c5)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff817e25ae)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef9ca)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f8cb0)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180de05)
Location: include/linux/pm_wakeup.h:86
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff811338a8)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8155de64)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff81565a41)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff81570c42)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c5db)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815b797d)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815b9e9b)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815bb7da)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c9b17)
Location: include/linux/pm_wakeup.h:73
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81628d0e)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686adb)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff816e528c)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff816eab75)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff816ec326)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff816f0b7c)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81710965)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81723d3e)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81724205)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff817246be)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817255e5)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81725e8f)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81726a71)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8172ae0e)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff817972cf)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff817bd905)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817c5078)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff817d00f5)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d15ba)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817de7a8)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f33eb)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f8771)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa04b)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fefe7)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81822f49)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830355)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff818398c4)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff8184feb5)
Location: include/linux/pm_wakeup.h:73
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8113f80b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8157eed4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff81586d41)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff81591e32)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff8159e03b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815d8bad)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815db0db)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815dca9a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ead37)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8164a7fe)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a91eb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff8170956c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff8170ebb5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81710396)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff8171501c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81734c55)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81747fde)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff817484a5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8174896e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81749895)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff8174a14f)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff8174ad31)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8174f00e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc4c5)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817ee265)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817f5a18)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81800fc5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8180248a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180f6f8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8182420b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818295d1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182ae8b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182fe47)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff818543e9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861c85)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186b234)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81881905)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8114e359)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff816244d4)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff8162de44)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff8163dc0b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81640722)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff81682bf5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff816856bb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff816871ab)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696929)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f98cd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b42b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff817c45bc)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca5b5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817cb9bb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff817d054c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f21e5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81805d4e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81806295)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8180677e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818077c5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81807eaf)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81808ca1)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8180d6ce)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff81883eaa)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818bda21)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818c5ad7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff818d16f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2fba)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e0408)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f5e1e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818fbeff)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fcd2b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81900f61)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81926b59)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935a25)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193ef46)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81950175)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8114a5e9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8164a094)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81653537)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff8166429b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81666b35)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff816a1255)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff816a346b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff816a4ebe)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3a79)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8171638d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8177650b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff817d909c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff817df065)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817e042b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff817e4bbc)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806795)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff8181658e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff818168b5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81816a8e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81817805)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81817e6f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81818b71)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8181c4be)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff8189258a)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818ca65c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818d19a7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff818dbad5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dd40a)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818ea268)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fe9ce)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81904a5f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8190565b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81909831)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff8192e6c9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193cad5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944ad6)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81955b35)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8114baa6)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8162cc64)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81635fd7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff8164681b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81648f15)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff81684045)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff8168626b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff81687c3f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81695cf9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f767d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a0eb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff817bd46f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff817c3465)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff817c4f8b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb3d5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff817faade)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff817fad15)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff817faeee)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbc75)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff817fc2af)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff817fcf91)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff817ff87e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff81874b9d)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818ad993)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818b4fc9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff818bee95)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c077a)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cbd78)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e211e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e820c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8e4b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee0d5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81911a89)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fd05)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81928299)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81939905)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8116f7b6)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8169e79f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff816a61e7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff816b80bb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba9f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff816f91f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff816fb57b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff816fd0c9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170ba05)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81771e1d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd62b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff818477ef)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d7d5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff8184f35b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81877d95)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81883fce)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81884205)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff818843de)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81885225)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff8188585f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81886a71)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff819055ed)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81942a60)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff8194a539)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff819554f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81956ec4)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81965558)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e350)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819845fc)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8198523b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198a885)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff819b32d9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c3095)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cba4f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff819de005)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff811a3cf5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff817c0609)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff817c8b03)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc24b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff817e02df)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff8182645d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff81828d59)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff8182a850)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81839f6d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff818a752d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c02c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff8198c31f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff81992ce5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff8199438d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c00e5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff819ccc0e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff819cce55)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff819cd06e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819cdf85)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff819ce63e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff819cf941)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy.c (ffffffff81a52424)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81a57c90)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a926)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81aa3237)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81aaeea5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0b29)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abf928)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad9a50)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adfbd5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae0e9b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae602b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81b12409)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23525)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2d2ba)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b42f55)
Location: include/linux/pm_wakeup.h:82
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
In kernel/time/alarmtimer.c (ffffffff811e3565)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff818dce19)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff818e617d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe14b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8190326c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff81957e3d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff8195ae89)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff8195cdad)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196f5cd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff819f176d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a77f8c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff81afbe1f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff81b03285)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81b04dad)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b359f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81b44dde)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81b45325)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81b4586e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46b25)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81b4730e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81b48871)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy.c (ffffffff81bdb7f4)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81be1b60)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff81c1f11e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81c28d67)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81c36995)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c37f61)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c492a8)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64b80)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6b1e5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c75b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c71d58)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81ca2eb9)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5ea7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0b9a)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cd9975)
Location: include/linux/pm_wakeup.h:82
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff811f7bb5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff819201cb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff819297bd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff819415fb)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8194690c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff8199e2fd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff819a1359)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff819a300d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b5b7d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a39e1d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2a3c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a20f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff81b51285)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81b52668)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b88e65)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81b9818e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81b986f5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81b98c3e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b99ef5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81b9a6de)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81b9bcd1)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy.c (ffffffff81c325d4)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81c39450)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff81c85ffd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81c8fd37)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81c9dc85)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f321)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb0888)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbf90)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd25d6)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3d4b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd91f1)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81d0a579)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d537)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d2856b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d41be5)
Location: include/linux/pm_wakeup.h:82
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff8120dd55)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8196835b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffffffff81971fbf)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a85b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8198fc3c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/acpi/wakeup.c (ffffffff819e699d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff819e9a09)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff819eb6bd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81a0009d)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a856cd)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14a0c)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff81ba25ff)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9875)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81baad18)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bdcd65)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff81bec15e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81bec6a5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81becbee)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bedea5)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81bee68e)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81befc91)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy.c (ffffffff81ce72c4)
Location: include/linux/pm_wakeup.h:82
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81cee7e0)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
```
In drivers/usb/core/hcd.c (ffffffff81d3aa8f)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81d448e7)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81d52835)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d53f71)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:suspend_common
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d65598)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80e70)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d87596)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88d0b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8e201)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81dc0209)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd3237)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde38b)
Location: include/linux/pm_wakeup.h:82
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df8595)
Location: include/linux/pm_wakeup.h:82
Inline: True
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
In kernel/time/alarmtimer.c (ffff8000101a9f98)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffff8000106e196c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (ffff8000106eb7f4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffff8000106f7934)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffff800010705f0c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffff800010765eb0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffff800010767260)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/soc/xilinx/zynqmp_pm_domains.c (ffff800010820a18)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffff800010880ddc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffff8000108f73b4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffff8000108ff050)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffff800010900a5c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffff8000109061f4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c410)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (ffff80001092f53c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/tc3589x.c (ffff800010930878)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_resume
  - drivers/mfd/tc3589x.c:tc3589x_suspend
```
```
In drivers/mfd/max14577.c (ffff800010944c98)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (ffff800010945ce0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (ffff800010945fb8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffff800010946480)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffff8000109472d8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffff800010947d00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffff800010948b00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffff80001094e090)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (ffff80001094f35c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/net/phy/phy_device.c (ffff8000109d54f4)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5f08)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1d2a4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffff800010a269b0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffff800010a35240)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a36c00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a38b88)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_resume
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a485c4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5ea68)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a65a44)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6c538)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad230)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_resume
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_suspend
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae214)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
```
```
In drivers/power/supply/charger-manager.c (ffff800010acdf18)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (c03f4d1c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/gpio/gpio-htc-egpio.c (c0869124)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_resume
  - drivers/gpio/gpio-htc-egpio.c:egpio_suspend
```
```
In drivers/pci/pci.c (c087d4c0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (c08863dc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pcie/pme.c (c089cc00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/tty/serial/serial_core.c (c0980fac)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/omap-serial.c (c099ec14)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_resume
  - drivers/tty/serial/omap-serial.c:serial_omap_suspend
```
```
In drivers/base/power/sysfs.c (c09e3330)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (c09e934c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (c09ead38)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (c09f0374)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (c0a0ae20)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (c0a10bbc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/tc3589x.c (c0a11c2c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_resume
  - drivers/mfd/tc3589x.c:tc3589x_suspend
```
```
In drivers/mfd/max14577.c (c0a2dea4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (c0a2ef30)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (c0a2f1d0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (c0a2f6b4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (c0a3061c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (c0a30ee8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (c0a31ba0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (c0a380f0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (c0a393d8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/net/phy/phy_device.c (c0abd044)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9280)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (c0af470c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (c0afca8c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (c0b0890c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (c0b0a0e0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0bef4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_resume
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_suspend
```
```
In drivers/usb/dwc2/hcd.c (c0b1ace0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-orion.c (c0b2fe04)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_suspend
```
```
In drivers/usb/host/ehci-exynos.c (c0b30330)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend
```
```
In drivers/usb/host/ohci-hcd.c (c0b36914)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-exynos.c (c0b383f8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend
```
```
In drivers/usb/host/uhci-hcd.c (c0b3ebc8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/rtc/rtc-omap.c (c0b8c298)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_resume
  - drivers/rtc/rtc-omap.c:omap_rtc_suspend
```
```
In drivers/rtc/rtc-s3c.c (c0b8deac)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_resume
  - drivers/rtc/rtc-s3c.c:s3c_rtc_suspend
```
```
In drivers/power/supply/charger-manager.c (c0bae7ec)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
```
```
In drivers/mmc/host/sdhci.c (c0c25920)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
```
```
In sound/soc/soc-jack.c (c0cad3a8)
Location: include/linux/pm_wakeup.h:77
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
In kernel/time/alarmtimer.c (c00000000020ce40)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (c00000000085ad00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pci-driver.c (c000000000867270)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/tty/serial/serial_core.c (c000000000929f50)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (c000000000992b60)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (c00000000099bf24)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (c00000000099e2ec)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (c0000000009a5268)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cb4b0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (c0000000009cf1e0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/tc3589x.c (c0000000009d08d8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_resume
  - drivers/mfd/tc3589x.c:tc3589x_suspend
```
```
In drivers/mfd/max14577.c (c0000000009eea68)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (c0000000009f0098)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (c0000000009f0430)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (c0000000009f0b08)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f1f90)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (c0000000009f2c08)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (c0000000009f3e5c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (c0000000009fa818)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (c0000000009fbcb8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/net/phy/phy_device.c (c000000000a96268)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (c000000000ad7734)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (c000000000ae2248)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (c000000000af2e58)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (c000000000af5710)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0db24)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b3558c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3ea50)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (c000000000b722f0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/power/supply/charger-manager.c (c000000000bb0b80)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffe000135220)
Location: include/linux/pm_wakeup.h:163
Inline: True
```
```
In drivers/pci/pci.c (ffffffe0004b9496)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3c98)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f492)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d1f0)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5f0c)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/max77693.c (ffffffe0005b838a)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max8997.c (ffffffe0005b9dbe)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffe0005baa42)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffe0006216f6)
Location: include/linux/pm_wakeup.h:163
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffe000641c9c)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffe00064884e)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffe000652a04)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffe0006655ea)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067fde8)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe00068616a)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cadd8)
Location: include/linux/pm_wakeup.h:163
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff81137fbb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff815733f4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-acpi.c (ffffffff81585cc2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff8159183b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815cbedd)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815cd8ab)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815cf0ea)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8161085e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166ec4b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff816cecbc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff816d4305)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff816d64f6)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff816db34c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/net/phy/phy_device.c (ffffffff81780f95)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817a6645)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817addf8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff817b93a5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ba86a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c7ad8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc5eb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817e19b1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e326b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8227)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81808b39)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181dee4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
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
In kernel/time/alarmtimer.c (ffffffff8112aa0b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff81561b54)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff815699a1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff81574a92)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff8158070b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815b4f2d)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815b742b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815b8caa)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5757)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81604dae)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164dc5b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff816a9fec)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff816af5a5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff816b0d86)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff816b59cc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/net/phy/phy_device.c (ffffffff81760d25)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81797a69)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff8179f7f8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff817aadd5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac28a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/input/serio/i8042.c (ffffffff817d0ba9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e5594)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
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
In kernel/time/alarmtimer.c (ffffffff81135cdb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff81572c24)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff8157aa91)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff81585b82)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff81591d8b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815cce8d)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815cf3bb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815d0d7a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df017)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8163e63e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169d02b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff816fd22c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff81702875)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff81704056)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff81708cdc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728115)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff8173b49e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8173b965)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8173be2e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173cd55)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff8173d60f)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff8173e1f1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff817424ce)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff817b1345)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817e30e5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817ea898)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff817f5e45)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f730a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81804578)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8181908b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181e451)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fd0b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81824cc7)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff81848579)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855e15)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185f3c4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81876db5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
In kernel/time/alarmtimer.c (ffffffff8114272b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/pci/pci.c (ffffffff8158d104)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_prepare_to_sleep
  - drivers/pci/pci.c:pci_enable_wake
```
```
In drivers/pci/pci-driver.c (ffffffff815950a1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/pci/pci-acpi.c (ffffffff815a0032)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
```
```
In drivers/pci/pcie/pme.c (ffffffff815abc3b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_check_wakeup
```
```
In drivers/acpi/wakeup.c (ffffffff815e6d2d)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_disable_wakeup_devices
  - drivers/acpi/wakeup.c:acpi_enable_wakeup_devices
```
```
In drivers/acpi/device_pm.c (ffffffff815e927b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
```
```
In drivers/acpi/proc.c (ffffffff815eac3a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f8ed7)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8165898e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b5fcb)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/sysfs.c (ffffffff81717abc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/wakeirq.c (ffffffff8171d095)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/base/power/main.c (ffffffff8171e156)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:pm_dev_dbg
```
```
In drivers/base/power/domain.c (ffffffff8172384c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743555)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/max14577.c (ffffffff817568de)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81756da5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8175726e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81758195)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/max8997.c (ffffffff81758a4f)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
```
```
In drivers/mfd/max8998.c (ffffffff81759631)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8175d90e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb2d5)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817fcb26)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81804ad8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/usb/core/phy.c (ffffffff81810085)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8181154a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq
  - drivers/usb/core/hcd-pci.c:hcd_pci_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181e688)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8183307b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81838141)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839c7b)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183d9f7)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:suspend_rh
```
```
In drivers/input/serio/i8042.c (ffffffff818637f9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870f45)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a244)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/power/supply/charger-manager.c (ffffffff81892755)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
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
