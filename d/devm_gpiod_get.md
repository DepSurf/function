# Function: <code>devm_gpiod_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81423a50)
Location: drivers/gpio/devres.c:62
Inline: False
```
**Symbols:**

```
ffffffff81423a50-ffffffff81423a64: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8146d060)
Location: drivers/gpio/devres.c:62
Inline: False
```
**Symbols:**

```
ffffffff8146d060-ffffffff8146d074: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8148ef30)
Location: drivers/gpio/devres.c:62
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8148ef30-ffffffff8148ef44: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814989d0)
Location: drivers/gpio/devres.c:64
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff814989d0-ffffffff814989e4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814d6cc0)
Location: drivers/gpio/devres.c:64
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff814d6cc0-ffffffff814d6cd4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81505dc0)
Location: drivers/gpio/devres.c:64
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff81505dc0-ffffffff81505dd4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815210f0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff815210f0-ffffffff81521104: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154f5f0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
**Symbols:**

```
ffffffff8154f5f0-ffffffff8154f604: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81570bb0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81570bb0-ffffffff81570bc4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81615090)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81615090-ffffffff816150a4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81639380)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
```
**Symbols:**

```
ffffffff81639380-ffffffff81639394: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161cfe0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff8161cfe0-ffffffff8161cff4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c470)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff8168c470-ffffffff8168c484: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a99e0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff817a99e0-ffffffff817a9a00: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c24a0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff818c24a0-ffffffff818c24c0: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff819053a0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff819053a0-ffffffff819053c0: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194cdb0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff8194cdb0-ffffffff8194cdd0: devm_gpiod_get (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c6b20)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
**Symbols:**

```
ffff8000106c6b20-ffff8000106c6b68: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0864598)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
**Symbols:**

```
c0864598-c08645bc: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c000000000843450)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
**Symbols:**

```
c000000000843450-c00000000084346c: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aa6c6)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
**Symbols:**

```
ffffffe0004aa6c6-ffffffe0004aa702: devm_gpiod_get (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81566370)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff81566370-ffffffff81566384: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815571c0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff815571c0-ffffffff815571d4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81564ee0)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff81564ee0-ffffffff81564ef4: devm_gpiod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get(struct device *dev, const char *con_id, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157ee00)
Location: drivers/gpio/gpiolib-devres.c:56
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
**Symbols:**

```
ffffffff8157ee00-ffffffff8157ee14: devm_gpiod_get (STB_GLOBAL)
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
