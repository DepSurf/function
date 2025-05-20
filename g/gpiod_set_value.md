# Function: <code>gpiod_set_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426520)
Location: drivers/gpio/gpiolib.c:1521
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
```
**Symbols:**

```
ffffffff81426520-ffffffff81426580: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fdc0)
Location: drivers/gpio/gpiolib.c:2479
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8146fdc0-ffffffff8146fe83: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81492130)
Location: drivers/gpio/gpiolib.c:2669
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff81492130-ffffffff814921f3: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149bae0)
Location: drivers/gpio/gpiolib.c:2666
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8149bae0-ffffffff8149bb80: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9e20)
Location: drivers/gpio/gpiolib.c:2940
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_set_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff814d9e20-ffffffff814d9ea4: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508bf0)
Location: drivers/gpio/gpiolib.c:3132
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff81508bf0-ffffffff81508c39: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d500)
Location: drivers/gpio/gpiolib.c:3297
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff8151d500-ffffffff8151d549: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3385
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff8154f055-ffffffff8154f068: gpiod_set_value.cold (STB_LOCAL)
ffffffff8154b5e0-ffffffff8154b62c: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c7d0)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8156c7d0-ffffffff8156c81c: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4145
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
**Symbols:**

```
ffffffff81614a01-ffffffff81614a62: gpiod_set_value.cold (STB_LOCAL)
ffffffff816109a0-ffffffff81610a00: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2969
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
**Symbols:**

```
ffffffff81bf626a-ffffffff81bf62cb: gpiod_set_value.cold (STB_LOCAL)
ffffffff81636d90-ffffffff81636df0: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2946
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
**Symbols:**

```
ffffffff81be8110-ffffffff81be8171: gpiod_set_value.cold (STB_LOCAL)
ffffffff8161a6b0-ffffffff8161a710: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2995
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
**Symbols:**

```
ffffffff81ce1cb5-ffffffff81ce1d2a: gpiod_set_value.cold (STB_LOCAL)
ffffffff81689ab0-ffffffff81689b1e: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3116
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
**Symbols:**

```
ffffffff81ea859f-ffffffff81ea8613: gpiod_set_value.cold (STB_LOCAL)
ffffffff817a6ab0-ffffffff817a6b39: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
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
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8208e5af-ffffffff8208e5c4: gpiod_set_value.cold (STB_LOCAL)
ffffffff818bece0-ffffffff818bedae: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3227
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8210e89c-ffffffff8210e8b1: gpiod_set_value.cold (STB_LOCAL)
ffffffff81901d90-ffffffff81901e50: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3420
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff821ec4ef-ffffffff821ec504: gpiod_set_value.cold (STB_LOCAL)
ffffffff819498d0-ffffffff81949990: gpiod_set_value (STB_GLOBAL)
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
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2400)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill
```
**Symbols:**

```
ffff8000106c2400-ffff8000106c2468: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860324)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/ata/sata_highbank.c:ecx_transmit_led_message
  - drivers/ata/sata_highbank.c:ecx_transmit_led_message
  - drivers/ata/sata_highbank.c:ecx_transmit_led_message
  - drivers/ata/sata_highbank.c:ecx_led_cycle_clock
  - drivers/ata/sata_highbank.c:ecx_led_cycle_clock
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill
```
**Symbols:**

```
c0860324-c0860394: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083daf0)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill
```
**Symbols:**

```
c00000000083daf0-c00000000083db78: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a7082)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_kill
```
**Symbols:**

```
ffffffe0004a7082-ffffffe0004a70da: gpiod_set_value (STB_GLOBAL)
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
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561f90)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff81561f90-ffffffff81561fdc: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552de0)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff81552de0-ffffffff81552e2c: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560b00)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff81560b00-ffffffff81560b4c: gpiod_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_set_value(struct gpio_desc *desc, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a9a0)
Location: drivers/gpio/gpiolib.c:3739
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_disable
  - drivers/clk/clk-gpio.c:clk_gpio_gate_enable
```
**Symbols:**

```
ffffffff8157a9a0-ffffffff8157a9ec: gpiod_set_value (STB_GLOBAL)
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
