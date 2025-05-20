# Function: <code>gpiochip_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425750)
Location: drivers/gpio/gpiolib.c:400
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_remove
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_remove
  - drivers/gpio/gpio-sx150x.c:sx150x_remove
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_remove
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_remove
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_remove
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff81425750-ffffffff8142592d: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f120)
Location: drivers/gpio/gpiolib.c:1229
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff8146f120-ffffffff8146f2d7: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491130)
Location: drivers/gpio/gpiolib.c:1310
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff81491130-ffffffff81491325: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149abf0)
Location: drivers/gpio/gpiolib.c:1303
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff8149abf0-ffffffff8149adcb: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9110)
Location: drivers/gpio/gpiolib.c:1331
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff814d9110-ffffffff814d9340: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508280)
Location: drivers/gpio/gpiolib.c:1438
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff81508280-ffffffff815084b4: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151cbc0)
Location: drivers/gpio/gpiolib.c:1468
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff8151cbc0-ffffffff8151ce55: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1487
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8154ef93-ffffffff8154efa7: gpiochip_remove.cold (STB_LOCAL)
ffffffff8154ae90-ffffffff8154af90: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8157053b-ffffffff8157054f: gpiochip_remove.cold (STB_LOCAL)
ffffffff8156c070-ffffffff8156c170: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1874
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib-devres.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
```
**Symbols:**

```
ffffffff816144eb-ffffffff816144ff: gpiochip_remove.cold (STB_LOCAL)
ffffffff8160f3b0-ffffffff8160f50b: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:821
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
```
**Symbols:**

```
ffffffff81bf5df1-ffffffff81bf5e05: gpiochip_remove.cold (STB_LOCAL)
ffffffff81635ec0-ffffffff81636015: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:810
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81be7b8d-ffffffff81be7ba1: gpiochip_remove.cold (STB_LOCAL)
ffffffff816194f0-ffffffff81619641: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:832
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81ce16c1-ffffffff81ce16d5: gpiochip_remove.cold (STB_LOCAL)
ffffffff816887f0-ffffffff81688935: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:862
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81ea7fa6-ffffffff81ea7fba: gpiochip_remove.cold (STB_LOCAL)
ffffffff817a5700-ffffffff817a5828: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd2f0)
Location: drivers/gpio/gpiolib.c:932
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff818bd2f0-ffffffff818bd436: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900630)
Location: drivers/gpio/gpiolib.c:963
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff81900630-ffffffff81900779: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *gc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947ee0)
Location: drivers/gpio/gpiolib.c:1044
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff81947ee0-ffffffff8194804c: gpiochip_remove (STB_GLOBAL)
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
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1380)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_remove
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffff8000106c1380-ffff8000106c14f4: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085ef24)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_remove
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove
  - drivers/gpio/gpio-omap.c:omap_gpio_remove
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_remove
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/sm501.c:sm501_dev_remove
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/asic3.c:asic3_remove
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - sound/soc/soc-ac97.c:snd_soc_free_ac97_component
```
**Symbols:**

```
c085ef24-c085f014: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083bf60)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
c00000000083bf60-c00000000083c104: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a5e7c)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_remove
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_remove
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffe0004a5e7c-ffffffe0004a5f88: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
```
**Symbols:**

```
ffffffff81565cfb-ffffffff81565d0f: gpiochip_remove.cold (STB_LOCAL)
ffffffff81561830-ffffffff81561930: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
```
**Symbols:**

```
ffffffff81556b4b-ffffffff81556b5f: gpiochip_remove.cold (STB_LOCAL)
ffffffff81552680-ffffffff81552780: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8156486b-ffffffff8156487f: gpiochip_remove.cold (STB_LOCAL)
ffffffff815603a0-ffffffff815604a0: gpiochip_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gpiochip_remove(struct gpio_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1496
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpio_chip_release
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8157e78b-ffffffff8157e79f: gpiochip_remove.cold (STB_LOCAL)
ffffffff8157a210-ffffffff8157a310: gpiochip_remove (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
</li>
</ul>
</details>
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
