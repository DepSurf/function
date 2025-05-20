# Function: <code>devm_gpiochip_add_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470e90)
Location: drivers/gpio/gpiolib.c:1308
Inline: False
Direct callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
**Symbols:**

```
ffffffff81470e90-ffffffff81470f1e: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81493000)
Location: drivers/gpio/gpiolib.c:1389
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
**Symbols:**

```
ffffffff81493000-ffffffff8149308e: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149c9b0)
Location: drivers/gpio/gpiolib.c:1381
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
**Symbols:**

```
ffffffff8149c9b0-ffffffff8149ca3e: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dafa0)
Location: drivers/gpio/gpiolib.c:1412
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
**Symbols:**

```
ffffffff814dafa0-ffffffff814db032: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150bc50)
Location: drivers/gpio/gpiolib.c:1520
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8150bc50-ffffffff8150bce2: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81520ad0)
Location: drivers/gpio/gpiolib.c:1537
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81520ad0-ffffffff81520b62: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154ebd0)
Location: drivers/gpio/gpiolib.c:1556
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8154ebd0-ffffffff8154ec63: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81570070)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81570070-ffffffff81570103: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c6338)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffff8000106c6338-ffff8000106c63e4: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08642f8)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/sh-pfc/gpio.c:sh_pfc_register_gpiochip
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-twl6040.c:gpo_twl6040_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
**Symbols:**

```
c08642f8-c0864388: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0000000008430b0)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
c0000000008430b0-c0000000008431a8: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004aa432)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffe0004aa432-ffffffe0004aa4ba: devm_gpiochip_add_data (STB_GLOBAL)
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
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81565830)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81565830-ffffffff815658c3: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81556680)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81556680-ffffffff81556713: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815643a0)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff815643a0-ffffffff81564433: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_gpiochip_add_data(struct device *dev, struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157e2c0)
Location: drivers/gpio/gpiolib.c:1565
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8157e2c0-ffffffff8157e353: devm_gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
