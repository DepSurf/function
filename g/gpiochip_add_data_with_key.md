# Function: <code>gpiochip_add_data_with_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da590)
Location: drivers/gpio/gpiolib.c:1115
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff814da590-ffffffff814daf92: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1230
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff8150bfee-ffffffff8150c05d: gpiochip_add_data_with_key.cold.54 (STB_LOCAL)
ffffffff8150b250-ffffffff8150bc4b: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1253
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff81520f1e-ffffffff81520f92: gpiochip_add_data_with_key.cold.52 (STB_LOCAL)
ffffffff815200a0-ffffffff81520aca: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1263
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8154f363-ffffffff8154f4a2: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8154e1e0-ffffffff8154ebc3: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8157086b-ffffffff81570a44: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8156f3e0-ffffffff8157006d: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1643
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib-devres.c:devm_gpiochip_add_data_with_key
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
```
**Symbols:**

```
ffffffff81614e44-ffffffff81614f2a: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff81613a40-ffffffff816140df: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:572
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_gpio
```
**Symbols:**

```
ffffffff81bf66e2-ffffffff81bf6803: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff81638930-ffffffff81639116: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:570
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81be85cf-ffffffff81be872b: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8161c450-ffffffff8161cd71: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:592
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81ce227c-ffffffff81ce23a4: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8168b970-ffffffff8168c1f1: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:593
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81ea8c98-ffffffff81ea8da5: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff817a8d70-ffffffff817a973b: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:650
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff8208e6a3-ffffffff8208e6b8: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff818c1680-ffffffff818c21a1: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:703
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff8210e9a6-ffffffff8210e9bb: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff81904600-ffffffff819050da: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:811
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff821ec5f8-ffffffff821ec60d: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8194c030-ffffffff8194caa4: gpiochip_add_data_with_key (STB_GLOBAL)
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
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c55a0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
**Symbols:**

```
ffff8000106c55a0-ffff8000106c6334: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c086369c)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/mfd/sm501.c:sm501_gpio_register_chip
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - sound/soc/soc-ac97.c:snd_soc_new_ac97_component
```
**Symbols:**

```
c086369c-c08642f8: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0000000008421b0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
c0000000008421b0-c0000000008430a4: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a9a02)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpiolib-of.c:of_mm_gpiochip_add_data
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffe0004a9a02-ffffffe0004aa432: gpiochip_add_data_with_key (STB_GLOBAL)
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
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
**Symbols:**

```
ffffffff8156602b-ffffffff81566204: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff81564ba0-ffffffff8156582d: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
```
**Symbols:**

```
ffffffff81556e7b-ffffffff81557054: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff815559f0-ffffffff8155667d: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff81564b9b-ffffffff81564d74: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff81563710-ffffffff8156439d: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_data_with_key(struct gpio_chip *chip, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1267
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
**Symbols:**

```
ffffffff8157eabb-ffffffff8157ec94: gpiochip_add_data_with_key.cold (STB_LOCAL)
ffffffff8157d630-ffffffff8157e2bd: gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
