# Function: <code>device_init_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c540)
Location: drivers/base/power/wakeup.c:438
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff8155c540-ffffffff8155c591: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae7c0)
Location: drivers/base/power/wakeup.c:436
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815ae7c0-ffffffff815ae825: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd5c0)
Location: drivers/base/power/wakeup.c:436
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core.c:i2c_device_remove
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815dd5c0-ffffffff815dd625: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f21b0)
Location: drivers/base/power/wakeup.c:438
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815f21b0-ffffffff815f2215: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659760)
Location: drivers/base/power/wakeup.c:440
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81659760-ffffffff816597b1: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816953c0)
Location: drivers/base/power/wakeup.c:444
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816953c0-ffffffff81695406: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5a30)
Location: drivers/base/power/wakeup.c:450
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816b5a30-ffffffff816b5a76: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef850)
Location: drivers/base/power/wakeup.c:434
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816ef850-ffffffff816ef899: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713870)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81713870-ffffffff817138b9: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf0c0)
Location: drivers/base/power/wakeup.c:513
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff817cf0c0-ffffffff817cf10d: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e36c0)
Location: drivers/base/power/wakeup.c:513
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff817e36c0-ffffffff817e370d: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7d00)
Location: drivers/base/power/wakeup.c:513
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff817c7d00-ffffffff817c7d4d: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81852120)
Location: drivers/base/power/wakeup.c:514
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81852120-ffffffff8185216d: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81998040)
Location: drivers/base/power/wakeup.c:514
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81998040-ffffffff819980e8: device_init_wakeup (STB_GLOBAL)
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
In kernel/time/alarmtimer.c (ffffffff811e35c3)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/scan.c (ffffffff81963537)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
```
```
In drivers/acpi/button.c (ffffffff819d0755)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/battery.c (ffffffff819de1e9)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_add
```
```
In drivers/mfd/max14577.c (ffffffff81b45034)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b45ab6)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46d8c)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b47515)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b48a13)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a6b3)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
```
In drivers/usb/core/hub.c (ffffffff81c18917)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81c6c5b5)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc1346)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc464c)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd75f1)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdb07d)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In kernel/time/alarmtimer.c (ffffffff811f7c13)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/scan.c (ffffffff819a99e7)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
```
```
In drivers/acpi/button.c (ffffffff81a17d82)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/battery.c (ffffffff81a25ee9)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_add
```
```
In drivers/mfd/max14577.c (ffffffff81b983e4)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b98e86)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a15c)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b9a8e5)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b9be77)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9daf3)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
```
In drivers/usb/core/hub.c (ffffffff81c7f8f7)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81cd3ba5)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28d0d)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c2bc)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f7c1)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d43355)
Location: include/linux/pm_wakeup.h:223
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In kernel/time/alarmtimer.c (ffffffff8120ddb3)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
```
```
In drivers/acpi/scan.c (ffffffff819f2487)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
```
```
In drivers/acpi/button.c (ffffffff81a62fe4)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/battery.c (ffffffff81a70b78)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_add
```
```
In drivers/mfd/max14577.c (ffffffff81bec3a8)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81bece36)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bee10c)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81bee880)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81befe22)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1ae3)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
```
In drivers/usb/core/hub.c (ffffffff81d342e7)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81d88b65)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81ddeb9c)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de218c)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df6171)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9cde)
Location: include/linux/pm_wakeup.h:233
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904cd0)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/rtc/rtc-mv.c:mv_rtc_remove
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_remove
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffff800010904cd0-ffff800010904d40: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09eeb38)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/rtc/rtc-mv.c:mv_rtc_remove
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_remove
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
**Symbols:**

```
c09eeb38-c09eeb94: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a36e0)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c0000000009a36e0-c0000000009a3768: device_init_wakeup (STB_GLOBAL)
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
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4fbc)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffe0005b06b8)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:add_numbered_child
```
```
In drivers/mfd/max14577.c (ffffffe0005b779a)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffe0005b89c6)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b9660)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9f9a)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005babb2)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bd156)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf178)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bff20)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/usb/core/hub.c (ffffffe00063c29e)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/host/ohci-pci.c (ffffffe0006806e4)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7544)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c914e)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cd26e)
Location: include/linux/pm_wakeup.h:156
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9ba0)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff816d9ba0-ffffffff816d9be9: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b4220)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
**Symbols:**

```
ffffffff816b4220-ffffffff816b4269: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81707530)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81707530-ffffffff81707579: device_init_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_init_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721f20)
Location: drivers/base/power/wakeup.c:454
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl-core.c:add_numbered_child
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81721f20-ffffffff81721f69: device_init_wakeup (STB_GLOBAL)
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
