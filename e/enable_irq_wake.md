# Function: <code>enable_irq_wake</code>

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
In drivers/pci/pcie/pme.c (ffffffff8144b685)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff8147b7c9)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81503dc2)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815582a1)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157a17d)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81583638)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588da6)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:356
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8158cfe8)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff8158e8c4)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8158ed89)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8158f263)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8159019a)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff81595bf4)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81596815)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81665a75)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8167744f)
Location: include/linux/interrupt.h:356
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
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
In drivers/pci/pcie/pme.c (ffffffff81497909)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff814c9e34)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff815553f1)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815aa3b1)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cf1dd)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d972d)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dde05)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:375
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff815e21f6)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff815e3774)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff815e3c3c)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff815e4113)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e501a)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff815eaa04)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff815eb5f5)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff816c5cfa)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d8033)
Location: include/linux/interrupt.h:375
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
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
In drivers/pci/pcie/pme.c (ffffffff814b9289)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff814ebd8f)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157e3c6)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815d9061)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fbe1d)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8160641d)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160aa95)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:395
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8160ee96)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81610624)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81610aec)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81610fc3)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611eca)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff81617814)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81618405)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff816f3d1a)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffe0f)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817081e4)
Location: include/linux/interrupt.h:395
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
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
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0739)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3a51)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff814f857d)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81595f58)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815edb71)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8160fbfd)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a20c)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161ebe2)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:404
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81622f96)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff816246ca)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81624b9c)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81625063)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625f3a)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8162b72a)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8162c2b9)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff817094da)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817156af)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171de04)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81781412)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5213)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814df148)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
```
In drivers/pci/pcie/pme.c (ffffffff81503c91)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff8153996d)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff815fab27)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81654f21)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167847d)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816828dc)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81687422)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:406
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8168b7f6)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff8168cfba)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8168d48c)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8168d953)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e82a)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8169406a)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81694c88)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff8177a68a)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817868cf)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178f087)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff817f79f2)
Location: include/linux/interrupt.h:406
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8150e173)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
```
In drivers/pci/pcie/pme.c (ffffffff81534f9f)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff8156f5cd)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81632c48)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8169083a)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b3f0c)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be95a)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c3488)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:404
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff816c78a6)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff816c90ba)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff816c959c)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff816c9a53)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ca9e9)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff816d01ba)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816d0d51)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff817bae8a)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c799f)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d18a3)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81840ff3)
Location: include/linux/interrupt.h:404
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81523485)
Location: include/linux/interrupt.h:420
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c1af)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff81587134)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81651be8)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0e9a)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d516c)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfd25)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e4878)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:420
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff816e8ca6)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff816ea63a)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff816eab1c)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff816eafd3)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebea9)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff816f17da)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816f23f4)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff817e22fa)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef03f)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f89f3)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8186cf43)
Location: include/linux/interrupt.h:420
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8155191b)
Location: include/linux/interrupt.h:449
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c5f1)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff815b7d94)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686868)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816eab3a)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817109c9)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8171940c)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171e1c7)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:449
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff817223fa)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81723d95)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81724269)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81724720)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81725646)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8172ae65)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8172b967)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81822d8e)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182fbaa)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8183962d)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818b0db3)
Location: include/linux/interrupt.h:449
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81572f9b)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8159e051)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff815d8d24)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a8f78)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8170eb7a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81734cb9)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d6fc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81742497)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8174669a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81748035)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81748509)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff817489d0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817498f6)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8174f065)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8174fbb7)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff8185422e)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818614da)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186af9d)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818e3243)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81616b7b)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff8163dc21)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff81682ee4)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759848)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca57a)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f2249)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817fb0ae)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffffa)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:465
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8180437a)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81805db5)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff818062f9)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff818067f0)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81807826)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8180d735)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8180e307)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff8192646e)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819351fa)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193ebfd)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b6323)
Location: include/linux/interrupt.h:465
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816318ab)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d4ae)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff816642b1)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff816a1354)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff817747b8)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817df017)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff818067f9)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d3fa)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81c13356)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:474
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81814dfa)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff818165e1)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81816919)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81816af0)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81817866)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8181c511)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8181cf17)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff8192dfee)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c26a)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944755)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b8863)
Location: include/linux/interrupt.h:474
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8161532b)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8162101d)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
```
In drivers/pci/pcie/pme.c (ffffffff81646831)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff81684144)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759e78)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817c3417)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb439)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1bad)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81c054bd)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:478
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff817f94da)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff817fab31)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff817fad79)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff817faf50)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbcd6)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff817ff8d1)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff818002a7)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff819113de)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f80a)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81927f85)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8199cf93)
Location: include/linux/interrupt.h:478
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167dc48)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816845bb)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816906f2)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
```
In drivers/pci/pcie/pme.c (ffffffff816b80d1)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff816f9324)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd3a8)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d787)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81877df9)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a80b)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81d0890c)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:451
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff8188294a)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81884021)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81884269)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81884440)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81885286)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8188a697)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff819b2adb)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c25ba)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cafe0)
Location: include/linux/interrupt.h:451
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81a49b0d)
Location: include/linux/interrupt.h:451
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff817996c8)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0c3b)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b03ca)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc261)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff818265d4)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191a904)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81930429)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81992c9f)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c0173)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c2f3b)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81ed0da5)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff819cb29a)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff819ccc71)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff819cced1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff819cd0e0)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819ce000)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff819d39a2)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81b11deb)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b2298a)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2cb76)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81bb7ef1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af808)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7e4b)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818c9e88)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe161)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff81958004)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a76354)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8e889)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81b0322f)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b35a93)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b3923c)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3da7a)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81b42d28)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81b44e51)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81b453b1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81b458f0)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46bb0)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81b4df78)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81ca2a0b)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc09e6)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81d5cbb1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2628)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818faebb)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190cf18)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81941611)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff8199e4ea)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac1104)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ada039)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81b51223)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b88f03)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8c6ac)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90f0a)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81b96098)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81b98201)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81b98781)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81b98cc0)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b99f80)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81ba1438)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81d0a0cb)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28399)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81dc7681)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939e58)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff819421eb)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954c18)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a871)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff819e6b8a)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b13f44)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2d329)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9813)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bdce03)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81be05ac)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4eaa)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:484
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81bea068)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81bec1d1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81bec731)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff81becc70)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bedf30)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81bf55c8)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81dbfd5b)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde1b9)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81e7ffe1)
Location: include/linux/interrupt.h:484
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475410)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cae04)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d1dcc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
```
```
In drivers/pci/pcie/pme.c (ffff800010705f1c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/tty/serial/serial_core.c (ffff800010880100)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892110)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend
```
```
In drivers/base/power/wakeirq.c (ffff8000108ff004)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c49c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (ffff80001092f59c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffff8000109389b8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093dcc0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e388)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffff800010943018)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffff800010944cf8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (ffff800010945d40)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (ffff80001094601c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffff8000109464e4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffff800010947364)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffff80001094e0f0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (ffff80001094f3b8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5f78)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad288)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_suspend
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae308)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffff800010b3db18)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpio-htc-egpio.c (c0869194)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_suspend
```
```
In drivers/gpio/gpio-mxc.c (c086bce8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
```
```
In drivers/gpio/gpio-vf610.c (c08736b4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_wake
```
```
In drivers/pci/pcie/pme.c (c089cc1c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/tty/serial/serial_core.c (c097dec8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d4c0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend
```
```
In drivers/base/power/wakeirq.c (c09e9314)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (c0a0aea8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (c0a10c24)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/wm831x-irq.c (c0a20e10)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/tps65217.c (c0a23438)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/twl4030-irq.c (c0a2673c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (c0a26e28)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (c0a2bebc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (c0a2df10)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (c0a2ef9c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (c0a2f238)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (c0a2f724)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (c0a306a4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (c0a3815c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (c0a3943c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac92b0)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b664a8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/rtc/rtc-omap.c (c0b8c344)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_suspend
```
```
In drivers/rtc/rtc-s3c.c (c0b8e508)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_suspend
```
```
In drivers/rtc/rtc-twl.c (c0b8f590)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
```
```
In drivers/mmc/core/slot-gpio.c (c0c18104)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
```
In drivers/mmc/host/sdhci.c (c0c259c8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
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
In drivers/tty/serial/serial_core.c (c000000000929960)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (c00000000099beb0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cb55c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/stmpe.c (c0000000009cf284)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df690)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5e0c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e68b0)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (c0000000009ec114)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (c0000000009eeb04)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77686.c (c0000000009f0134)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_suspend
```
```
In drivers/mfd/max77693.c (c0000000009f0504)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (c0000000009f0bb0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f203c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (c0000000009fa8b4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/as3722.c (c0000000009fbd44)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_suspend
```
```
In drivers/input/serio/i8042.c (c000000000b71818)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/mmc/core/slot-gpio.c (c000000000c3b1ec)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/pci/pcie/pme.c (ffffffe0004d3ca8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f288)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d1ac)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5f62)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad6e6)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1df8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b23bc)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffe0005b5eac)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max77693.c (ffffffe0005b83e6)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffe000714b60)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8156875b)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81591851)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166e9d8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816d42ca)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817011dc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/da9052-irq.c (ffffffff8170370a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/input/serio/i8042.c (ffffffff81808b9c)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181dc4d)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81886c03)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff815595ab)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81580721)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff815b50a4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164cad8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816af56a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4fec)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/da9052-irq.c (ffffffff816d750a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/input/serio/i8042.c (ffffffff817d09ee)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e52f7)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
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
In drivers/gpio/gpiolib-acpi.c (ffffffff815672cb)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff81591da1)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff815cd004)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169cdb8)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8170283a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728179)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730bbc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81735957)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81739b5a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff8173b4f5)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff8173b9c9)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff8173be90)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173cdb6)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff81742525)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81743077)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff818483be)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185566a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185f12d)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818d80a3)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
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
In drivers/gpio/gpiolib-acpi.c (ffffffff815811eb)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff815abc51)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
```
In drivers/acpi/sleep.c (ffffffff815e6ea4)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3b48)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_suspend_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8171d05a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817435b9)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_suspend
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bffc)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750d97)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:450
Inline: True
```
```
In drivers/mfd/da9052-irq.c (ffffffff81754f9a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/da9052-irq.c:da9052_irq_init
```
```
In drivers/mfd/max14577.c (ffffffff81756935)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_suspend
```
```
In drivers/mfd/max77693.c (ffffffff81756e09)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_suspend
```
```
In drivers/mfd/max77843.c (ffffffff817572d0)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_suspend
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817581f6)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_suspend
```
```
In drivers/mfd/sec-core.c (ffffffff8175d965)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_suspend
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8175e4c7)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/input/serio/i8042.c (ffffffff8186363e)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187079a)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81879c44)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_suspend
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818f4bc3)
Location: include/linux/interrupt.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
</details>
</li>
</ul>

## Differences
