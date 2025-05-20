# Function: <code>gpio_to_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424ee0)
Location: drivers/gpio/gpiolib.c:68
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/spi/spi.c:spi_set_cs
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_regs
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81424ee0-ffffffff81424fb9: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ed30)
Location: drivers/gpio/gpiolib.c:85
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8146ed30-ffffffff8146ee12: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490d00)
Location: drivers/gpio/gpiolib.c:88
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff81490d00-ffffffff81490de2: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a6d0)
Location: drivers/gpio/gpiolib.c:89
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_request_gpio
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff8149a6d0-ffffffff8149a78f: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d89e0)
Location: drivers/gpio/gpiolib.c:97
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_suspend
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff814d89e0-ffffffff814d8ab8: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81507f30)
Location: drivers/gpio/gpiolib.c:105
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro
```
**Symbols:**

```
ffffffff81507f30-ffffffff81508008: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c920)
Location: drivers/gpio/gpiolib.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/regulator/core.c:regulator_register
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8151c920-ffffffff8151c9f8: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154ac00)
Location: drivers/gpio/gpiolib.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8154ac00-ffffffff8154acd4: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156baf0)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8156baf0-ffffffff8156bbc4: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160ca90)
Location: drivers/gpio/gpiolib.c:108
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8160ca90-ffffffff8160cb63: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:105
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81bf59e5-ffffffff81bf59fb: gpio_to_desc.cold (STB_LOCAL)
ffffffff816337a0-ffffffff8163384a: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:107
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81be7903-ffffffff81be7919: gpio_to_desc.cold (STB_LOCAL)
ffffffff81617490-ffffffff8161753b: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:107
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81ce13cf-ffffffff81ce13e5: gpio_to_desc.cold (STB_LOCAL)
ffffffff81686710-ffffffff816867bb: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:107
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81ea7b9f-ffffffff81ea7bb3: gpio_to_desc.cold (STB_LOCAL)
ffffffff817a3530-ffffffff817a35f3: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818baa50)
Location: drivers/gpio/gpiolib.c:108
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff818baa50-ffffffff818bab1c: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fdb50)
Location: drivers/gpio/gpiolib.c:125
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff818fdb50-ffffffff818fdc1c: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81945100)
Location: drivers/gpio/gpiolib.c:113
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81945100-ffffffff819451ca: gpio_to_desc (STB_GLOBAL)
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
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0758)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
ffff8000106c0758-ffff8000106c08c0: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f49c)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
```
**Symbols:**

```
c085f49c-c085f580: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083cb60)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
c00000000083cb60-c00000000083ccb0: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a657e)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffe0004a657e-ffffffe0004a6652: gpio_to_desc (STB_GLOBAL)
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
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815612b0)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff815612b0-ffffffff81561384: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552100)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81552100-ffffffff815521d4: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fe20)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8155fe20-ffffffff8155fef4: gpio_to_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpio_to_desc(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81579c90)
Location: drivers/gpio/gpiolib.c:108
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_free_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request_array
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81579c90-ffffffff81579d64: gpio_to_desc (STB_GLOBAL)
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
