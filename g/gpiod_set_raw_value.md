# Function: <code>gpiod_set_raw_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814264d0)
Location: drivers/gpio/gpiolib.c:1500
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff814264d0-ffffffff8142651d: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fd10)
Location: drivers/gpio/gpiolib.c:2459
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8146fd10-ffffffff8146fdba: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81492080)
Location: drivers/gpio/gpiolib.c:2649
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff81492080-ffffffff8149212a: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149ba50)
Location: drivers/gpio/gpiolib.c:2646
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff8149ba50-ffffffff8149bade: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9f30)
Location: drivers/gpio/gpiolib.c:2899
Inline: True
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
  - drivers/i2c/i2c-core-base.c:set_scl_gpio_value
```
**Symbols:**

```
ffffffff814d9f30-ffffffff814d9fbe: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508900)
Location: drivers/gpio/gpiolib.c:3091
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff81508900-ffffffff8150894f: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d410)
Location: drivers/gpio/gpiolib.c:3256
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_remove
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/spi/spi.c:spi_set_cs
```
**Symbols:**

```
ffffffff8151d410-ffffffff8151d45f: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3344
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8154f068-ffffffff8154f07b: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff8154b630-ffffffff8154b67e: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c6e0)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8156c6e0-ffffffff8156c72e: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4104
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81614b3d-ffffffff81614b9e: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff81610af0-ffffffff81610b52: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2928
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81bf63a6-ffffffff81bf6407: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff81636ef0-ffffffff81636f52: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2905
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81be824c-ffffffff81be82ad: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff8161a810-ffffffff8161a872: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2954
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81ce1e19-ffffffff81ce1e8f: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff81689c30-ffffffff81689ca5: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3075
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81ea8613-ffffffff81ea8687: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff817a6b40-ffffffff817a6bcf: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3145
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8208e5c4-ffffffff8208e5d9: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff818bedc0-ffffffff818bee94: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3186
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8210e8c6-ffffffff8210e8db: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff81902040-ffffffff81902106: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3379
Inline: False
Direct callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff821ec519-ffffffff821ec52e: gpiod_set_raw_value.cold (STB_LOCAL)
ffffffff81949a70-ffffffff81949b36: gpiod_set_raw_value (STB_GLOBAL)
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
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfad0)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffff8000106bfad0-ffff8000106bfb3c: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c086020c)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
c086020c-c0860280: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d950)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
c00000000083d950-c00000000083d9e8: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6f64)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffe0004a6f64-ffffffe0004a6fbe: gpiod_set_raw_value (STB_GLOBAL)
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
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561ea0)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
```
**Symbols:**

```
ffffffff81561ea0-ffffffff81561eee: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552cf0)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
```
**Symbols:**

```
ffffffff81552cf0-ffffffff81552d3e: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560a10)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff81560a10-ffffffff81560a5e: gpiod_set_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_raw_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a8b0)
Location: drivers/gpio/gpiolib.c:3698
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/aat2870-core.c:aat2870_i2c_resume
  - drivers/mfd/aat2870-core.c:aat2870_i2c_suspend
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
**Symbols:**

```
ffffffff8157a8b0-ffffffff8157a8fe: gpiod_set_raw_value (STB_GLOBAL)
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
