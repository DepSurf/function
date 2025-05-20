# Function: <code>gpiod_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814241d0)
Location: drivers/gpio/gpiolib.c:1597
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff814241d0-ffffffff81424208: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146dcf0)
Location: drivers/gpio/gpiolib.c:2553
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8146dcf0-ffffffff8146dd54: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fbb0)
Location: drivers/gpio/gpiolib.c:2743
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8148fbb0-ffffffff8148fc14: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814994e0)
Location: drivers/gpio/gpiolib.c:2740
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff814994e0-ffffffff81499543: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d77e0)
Location: drivers/gpio/gpiolib.c:3011
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff814d77e0-ffffffff814d7846: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815064e0)
Location: drivers/gpio/gpiolib.c:3203
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff815064e0-ffffffff81506540: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151a990)
Location: drivers/gpio/gpiolib.c:3396
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8151a990-ffffffff8151a9f0: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81549030)
Location: drivers/gpio/gpiolib.c:3485
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff81549030-ffffffff81549092: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a0b0)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8156a0b0-ffffffff8156a112: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160ca20)
Location: drivers/gpio/gpiolib.c:4245
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8160ca20-ffffffff8160ca82: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816338b0)
Location: drivers/gpio/gpiolib.c:3069
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff816338b0-ffffffff8163391e: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816175a0)
Location: drivers/gpio/gpiolib.c:3046
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff816175a0-ffffffff81617610: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81686810)
Location: drivers/gpio/gpiolib.c:3095
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff81686810-ffffffff81686889: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a3010)
Location: drivers/gpio/gpiolib.c:3216
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff817a3010-ffffffff817a30c9: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba470)
Location: drivers/gpio/gpiolib.c:3286
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff818ba470-ffffffff818ba529: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd570)
Location: drivers/gpio/gpiolib.c:3327
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff818fd570-ffffffff818fd629: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944b00)
Location: drivers/gpio/gpiolib.c:3520
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff81944b00-ffffffff81944bb6: gpiod_to_irq (STB_GLOBAL)
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
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bda98)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffff8000106bda98-ffff8000106bdb0c: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d444)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
**Symbols:**

```
c085d444-c085d4b4: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839990)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
c000000000839990-c000000000839a40: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4574)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffe0004a4574-ffffffe0004a45ca: gpiod_to_irq (STB_GLOBAL)
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
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f870)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8155f870-ffffffff8155f8d2: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815506c0)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff815506c0-ffffffff81550722: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e3e0)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff8155e3e0-ffffffff8155e442: gpiod_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_to_irq(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578270)
Location: drivers/gpio/gpiolib.c:3839
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib-sysfs.c:gpio_is_visible
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq
```
**Symbols:**

```
ffffffff81578270-ffffffff815782d2: gpiod_to_irq (STB_GLOBAL)
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
