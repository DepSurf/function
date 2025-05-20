# Function: <code>irq_set_irq_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810daf20)
Location: kernel/irq/manage.c:589
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff810daf20-ffffffff810db04c: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e05b0)
Location: kernel/irq/manage.c:603
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
**Symbols:**

```
ffffffff810e05b0-ffffffff810e06dd: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6f00)
Location: kernel/irq/manage.c:603
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
**Symbols:**

```
ffffffff810e6f00-ffffffff810e701e: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6600)
Location: kernel/irq/manage.c:580
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff810e6600-ffffffff810e6723: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee8b0)
Location: kernel/irq/manage.c:608
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff810ee8b0-ffffffff810ee9d3: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6cb0)
Location: kernel/irq/manage.c:641
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff810f6cb0-ffffffff810f6dd1: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102420)
Location: kernel/irq/manage.c:644
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81102420-ffffffff81102541: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110ac00)
Location: kernel/irq/manage.c:702
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff8110ac00-ffffffff8110ad3d: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116fd0)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81116fd0-ffffffff8111710d: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81123010)
Location: kernel/irq/manage.c:778
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81123010-ffffffff811231b6: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ed20)
Location: kernel/irq/manage.c:848
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff8111ed20-ffffffff8111eec6: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111efa0)
Location: kernel/irq/manage.c:848
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff8111efa0-ffffffff8111f146: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113f430)
Location: kernel/irq/manage.c:872
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
**Symbols:**

```
ffffffff8113f430-ffffffff8113f5d6: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162ec0)
Location: kernel/irq/manage.c:887
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81162ec0-ffffffff81163068: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81196ac0)
Location: kernel/irq/manage.c:879
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81196ac0-ffffffff81196c68: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a8480)
Location: kernel/irq/manage.c:885
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff811a8480-ffffffff811a8628: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b7f00)
Location: kernel/irq/manage.c:887
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff811b7f00-ffffffff811b80a8: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010178f20)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-pl061.c:pl061_irq_set_wake
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_resume
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_suspend
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffff800010178f20-ffff80001017906c: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03caa10)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/gpio/gpio-htc-egpio.c:egpio_resume
  - drivers/gpio/gpio-htc-egpio.c:egpio_suspend
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_wake_enable
  - drivers/gpio/gpio-pl061.c:pl061_irq_set_wake
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_wake
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_wake
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_free
  - drivers/rtc/rtc-omap.c:omap_rtc_resume
  - drivers/rtc/rtc-omap.c:omap_rtc_suspend
  - drivers/rtc/rtc-s3c.c:s3c_rtc_resume
  - drivers/rtc/rtc-s3c.c:s3c_rtc_suspend
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/host/sdhci.c:sdhci_resume_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
**Symbols:**

```
c03caa10-c03cab5c: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d34f0)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77686.c:max77686_resume
  - drivers/mfd/max77686.c:max77686_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/as3722.c:as3722_i2c_resume
  - drivers/mfd/as3722.c:as3722_i2c_suspend
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
c0000000001d34f0-c0000000001d369c: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113a5a)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/stmpe.c:stmpe_resume
  - drivers/mfd/stmpe.c:stmpe_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffe000113a5a-ffffffe000113b38: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f5b0)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff8110f5b0-ffffffff8110f6ed: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811002f0)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
**Symbols:**

```
ffffffff811002f0-ffffffff8110042d: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d4a0)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff8110d4a0-ffffffff8110d5dd: irq_set_irq_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118a00)
Location: kernel/irq/manage.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/88pm860x-core.c:pm860x_resume
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_set_wake
  - drivers/mfd/arizona-irq.c:arizona_set_irq_wake
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-irq.c:da9052_irq_init
  - drivers/mfd/max14577.c:max14577_resume
  - drivers/mfd/max14577.c:max14577_suspend
  - drivers/mfd/max77693.c:max77693_resume
  - drivers/mfd/max77693.c:max77693_suspend
  - drivers/mfd/max77843.c:max77843_resume
  - drivers/mfd/max77843.c:max77843_suspend
  - drivers/mfd/max8925-i2c.c:max8925_resume
  - drivers/mfd/max8925-i2c.c:max8925_suspend
  - drivers/mfd/max8997.c:max8997_resume
  - drivers/mfd/max8997.c:max8997_suspend
  - drivers/mfd/max8998.c:max8998_resume
  - drivers/mfd/max8998.c:max8998_suspend
  - drivers/mfd/tps6586x.c:tps6586x_irq_set_wake
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake
  - drivers/mfd/sec-core.c:sec_pmic_resume
  - drivers/mfd/sec-core.c:sec_pmic_suspend
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/input/serio/i8042.c:i8042_pm_resume
  - drivers/input/serio/i8042.c:i8042_pm_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
**Symbols:**

```
ffffffff81118a00-ffffffff81118b3d: irq_set_irq_wake (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
