# Function: <code>disable_irq_wake</code>

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
In drivers/pci/pcie/pme.c (ffffffff8144bb41)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff8147b796)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff81503ab1)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815582e1)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157a12d)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:361
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff8158e884)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff8158ed49)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff8158f214)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8159015a)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff81595bb4)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff8166592c)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81677593)
Location: include/linux/interrupt.h:361
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/pci/pcie/pme.c (ffffffff81497de1)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff814c9e01)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff815550d1)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815aa3f1)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cf18d)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:380
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff815e3734)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff815e3bfc)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff815e40c4)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e4fda)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff815ea9c4)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff816c5ba1)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d8167)
Location: include/linux/interrupt.h:380
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/pci/pcie/pme.c (ffffffff814b9691)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff814ebd5c)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff81581d95)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815d90a1)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fbdcd)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:400
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff816105e4)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81610aac)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81610f74)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611e8a)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff816177d4)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff816f3bc1)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8170089f)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81708595)
Location: include/linux/interrupt.h:400
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8149f9d7)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3e81)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff814f8504)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff815961e5)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff815edbc1)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8160fbad)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:409
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff8162468a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81624b5c)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff8162501a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625efa)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8162b6ea)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81709711)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8171610f)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171e1bc)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/core.c (ffffffff81774eee)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d526a)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de45b)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff815040c1)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815398f4)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff815fb041)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81654f71)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167842d)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:411
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff8168cf7a)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff8168d44c)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff8168d90a)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e7ea)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8169402a)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff8177a8c1)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8178730f)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178f43f)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/core.c (ffffffff817eb196)
Location: include/linux/interrupt.h:411
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8150d749)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81534f62)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff8156f554)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
```
```
In drivers/tty/serial/serial_core.c (ffffffff81633185)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8169088a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b3ebc)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:409
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff816c907a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff816c9559)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff816c9a0a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ca9a9)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff816d017a)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff817bb151)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c83c6)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d1d23)
Location: include/linux/interrupt.h:409
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81841013)
Location: include/linux/interrupt.h:409
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81522ebf)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c602)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff81587189)
Location: include/linux/interrupt.h:425
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81652285)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0eea)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d511c)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:425
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff816ea5fa)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff816eaad9)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff816eaf8a)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebe69)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff816f179a)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff817e25c1)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817efa66)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f8e81)
Location: include/linux/interrupt.h:425
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8186cf63)
Location: include/linux/interrupt.h:425
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
In drivers/gpio/gpiolib-acpi.c (ffffffff815513a0)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c6f9)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815b7e00)
Location: include/linux/interrupt.h:454
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686d95)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816eab88)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81710989)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:454
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81723d55)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81724226)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff817246d5)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81725606)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8172ae25)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81822f5c)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818303d8)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81839a81)
Location: include/linux/interrupt.h:454
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818b0dd1)
Location: include/linux/interrupt.h:454
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81572960)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff8159e159)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815d8f60)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a94a5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8170ebc8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81734c79)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81747ff5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff817484c6)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81748985)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817498b6)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8174f025)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff818543fc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861d08)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186b3f1)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818e3261)
Location: include/linux/interrupt.h:455
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81616d3e)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff8163db65)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff81683030)
Location: include/linux/interrupt.h:470
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b6ab)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca5c8)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f2209)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:470
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81805d65)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff818062b6)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81806795)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818077e6)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8180d6e5)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81926b6c)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935ad4)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193f0ea)
Location: include/linux/interrupt.h:470
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b6341)
Location: include/linux/interrupt.h:470
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816318c3)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d66e)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff816641f5)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff816a1600)
Location: include/linux/interrupt.h:479
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8177678b)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817df078)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff818067b9)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:479
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff818165a1)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff818168d6)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81816aa1)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81817826)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8181c4d1)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff8192e6dc)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193cb84)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944c7a)
Location: include/linux/interrupt.h:479
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b8881)
Location: include/linux/interrupt.h:479
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615343)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816212ee)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81646665)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff81684480)
Location: include/linux/interrupt.h:483
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a36b)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817c3478)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb3f9)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:483
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff817faaf1)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff817fad36)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff817faf01)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbc96)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff817ff891)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81911a9c)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fdb4)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81928468)
Location: include/linux/interrupt.h:483
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8199cfb1)
Location: include/linux/interrupt.h:483
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167dc5f)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816845d0)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff816909f6)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7f63)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff816f9750)
Location: include/linux/interrupt.h:456
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd8df)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d7e8)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81877db9)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:456
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81883fe1)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81884226)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff818843f1)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81885246)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/input/serio/i8042.c (ffffffff819b32f2)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c3160)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cbd36)
Location: include/linux/interrupt.h:456
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81a49b27)
Location: include/linux/interrupt.h:456
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff817996eb)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0c5f)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817afc1b)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc376)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff8182687a)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c2c6)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff819304c9)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81992cf8)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c0113)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff819ccc21)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff819cce7e)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff819cd081)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819cdfb0)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81b12422)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23615)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2d4cf)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81bb7f13)
Location: include/linux/interrupt.h:489
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af849)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7e6f)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818c942b)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe286)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff8195847a)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78245)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8e939)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81b03298)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b35a23)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81b44df1)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81b4534e)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81b45881)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46b50)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81ca2ed2)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0dab)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81d5cbd3)
Location: include/linux/interrupt.h:489
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2669)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818faedf)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190c4eb)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81941736)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff8199eb9a)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2cf5)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ada0e9)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81b51298)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b88e93)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81b981a1)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81b9871e)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81b98c51)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b99f20)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81d0a592)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28777)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81dc76a3)
Location: include/linux/interrupt.h:489
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939e99)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8194220f)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff819540db)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a996)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff819e723a)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14cc9)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2d3d9)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9888)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bdcd93)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:489
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff81bec171)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81bec6ce)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81becc01)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81beded0)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/input/serio/i8042.c (ffffffff81dc0222)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde597)
Location: include/linux/interrupt.h:489
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81e80003)
Location: include/linux/interrupt.h:489
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
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca70c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d1de8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
```
```
In drivers/pci/pcie/pme.c (ffff8000107060a0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/tty/serial/serial_core.c (ffff8000108810dc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892094)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume
```
```
In drivers/base/power/wakeirq.c (ffff8000108ff060)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c43c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/stmpe.c (ffff80001092f54c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e370)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (ffff800010944ca8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77686.c (ffff800010945cf0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
```
```
In drivers/mfd/max77693.c (ffff800010945fcc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffff800010946490)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffff800010947304)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffff80001094e0a0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/mfd/as3722.c (ffff80001094f36c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e5f5c)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad240)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_resume
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae288)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffff800010b3db44)
Location: include/linux/interrupt.h:455
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
In drivers/gpio/gpio-htc-egpio.c (c086913c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_resume
```
```
In drivers/gpio/gpio-mxc.c (c086bcfc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
  - drivers/gpio/gpio-mxc.c:gpio_set_wake_irq
```
```
In drivers/gpio/gpio-vf610.c (c08736b4)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_wake
```
```
In drivers/pci/pcie/pme.c (c089cf8c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/tty/serial/serial_core.c (c098125c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d45c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume
```
```
In drivers/base/power/wakeirq.c (c09e9364)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (c0a0ae50)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/stmpe.c (c0a10bd4)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
```
```
In drivers/mfd/twl6030-irq.c (c0a26e14)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (c0a2dec0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77686.c (c0a2ef4c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
```
```
In drivers/mfd/max77693.c (c0a2f1ec)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (c0a2f6d0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (c0a3064c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (c0a3810c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/mfd/as3722.c (c0a393f0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac92e0)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b65468)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_free
```
```
In drivers/rtc/rtc-omap.c (c0b8c2b0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_resume
```
```
In drivers/rtc/rtc-s3c.c (c0b8ded8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_resume
```
```
In drivers/rtc/rtc-twl.c (c0b8f578)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
```
```
In drivers/mmc/core/slot-gpio.c (c0c18124)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
```
In drivers/mmc/host/sdhci.c (c0c2539c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_resume_host
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
In drivers/tty/serial/serial_core.c (c00000000092a2c0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (c00000000099bf3c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cb4ec)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/stmpe.c (c0000000009cf204)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e6898)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (c0000000009eea84)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77686.c (c0000000009f00b4)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_resume
```
```
In drivers/mfd/max77693.c (c0000000009f0474)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (c0000000009f0b24)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f1fcc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (c0000000009fa834)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/mfd/as3722.c (c0000000009fbcd0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_resume
```
```
In drivers/input/serio/i8042.c (c000000000b72308)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/mmc/core/slot-gpio.c (c000000000c3b270)
Location: include/linux/interrupt.h:455
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
In drivers/pci/pcie/pme.c (ffffffe0004d419e)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f6e4)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d200)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5f1c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_resume
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b23a8)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max77693.c (ffffffe0005b839c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffe000714b84)
Location: include/linux/interrupt.h:455
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81568120)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81591959)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166ef05)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816d4318)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/input/serio/i8042.c (ffffffff81808b4c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181e0a1)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81886c21)
Location: include/linux/interrupt.h:455
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81558f70)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81580b03)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815b5450)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164df09)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816af5b8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/input/serio/i8042.c (ffffffff817d0bbc)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e5747)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81566c90)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff81591ea9)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815cd240)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169d2e5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81702888)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728139)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff8173b4b5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff8173b986)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff8173be45)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173cd76)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff817424e5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff8184858c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855e98)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185f581)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818d80c1)
Location: include/linux/interrupt.h:455
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81580bb0)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pci/pcie/pme.c (ffffffff815abf80)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
```
```
In drivers/acpi/sleep.c (ffffffff815e70e0)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b6273)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8171d0a8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743579)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_resume
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/interrupt.h:455
Inline: True
```
```
In drivers/mfd/max14577.c (ffffffff817568f5)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_resume
```
```
In drivers/mfd/max77693.c (ffffffff81756dc6)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_resume
```
```
In drivers/mfd/max77843.c (ffffffff81757285)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_resume
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817581b6)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_resume
```
```
In drivers/mfd/sec-core.c (ffffffff8175d925)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_resume
```
```
In drivers/input/serio/i8042.c (ffffffff8186380c)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870fc8)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a3f4)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818f4be1)
Location: include/linux/interrupt.h:455
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake
```
</details>
</li>
</ul>

## Differences
