# Function: <code>gpiod_get_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425c60)
Location: drivers/gpio/gpiolib.c:1323
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
```
**Symbols:**

```
ffffffff81425c60-ffffffff81425cb4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f7a0)
Location: drivers/gpio/gpiolib.c:2281
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
```
**Symbols:**

```
ffffffff8146f7a0-ffffffff8146f85a: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491b10)
Location: drivers/gpio/gpiolib.c:2471
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
```
**Symbols:**

```
ffffffff81491b10-ffffffff81491bca: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b320)
Location: drivers/gpio/gpiolib.c:2475
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
```
**Symbols:**

```
ffffffff8149b320-ffffffff8149b3dd: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da1c0)
Location: drivers/gpio/gpiolib.c:2688
Inline: True
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_mux_get_parent
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
```
**Symbols:**

```
ffffffff814da1c0-ffffffff814da27d: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509000)
Location: drivers/gpio/gpiolib.c:2864
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81509000-ffffffff81509054: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d6a0)
Location: drivers/gpio/gpiolib.c:2983
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8151d6a0-ffffffff8151d6f4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3071
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8154f08e-ffffffff8154f0a1: gpiod_get_value.cold (STB_LOCAL)
ffffffff8154ba00-ffffffff8154ba54: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c990)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8156c990-ffffffff8156c9e4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3837
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81614b9e-ffffffff81614c06: gpiod_get_value.cold (STB_LOCAL)
ffffffff81610b60-ffffffff81610bce: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2662
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81bf6407-ffffffff81bf646f: gpiod_get_value.cold (STB_LOCAL)
ffffffff81636f60-ffffffff81636fce: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2639
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81be82ad-ffffffff81be8315: gpiod_get_value.cold (STB_LOCAL)
ffffffff8161a880-ffffffff8161a8ee: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2679
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81ce1e8f-ffffffff81ce1f0c: gpiod_get_value.cold (STB_LOCAL)
ffffffff81689cb0-ffffffff81689d2e: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2800
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81ea86f7-ffffffff81ea8774: gpiod_get_value.cold (STB_LOCAL)
ffffffff817a6c70-ffffffff817a6cf9: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2870
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8208e5d9-ffffffff8208e5ee: gpiod_get_value.cold (STB_LOCAL)
ffffffff818bf0b0-ffffffff818bf194: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2911
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8210e8db-ffffffff8210e8f0: gpiod_get_value.cold (STB_LOCAL)
ffffffff819021e0-ffffffff819022b6: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3104
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff821ec52e-ffffffff821ec543: gpiod_get_value.cold (STB_LOCAL)
ffffffff81949d20-ffffffff81949df6: gpiod_get_value (STB_GLOBAL)
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
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfcf8)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffff8000106bfcf8-ffff8000106bfd70: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860534)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mtd/nand/raw/omap2.c:omap_dev_ready
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_resume
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
```
**Symbols:**

```
c0860534-c08605b4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ddf0)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c00000000083ddf0-c00000000083de70: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a722e)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffe0004a722e-ffffffe0004a728e: gpiod_get_value (STB_GLOBAL)
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
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562150)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81562150-ffffffff815621a4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552fa0)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
```
**Symbols:**

```
ffffffff81552fa0-ffffffff81552ff4: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560cc0)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81560cc0-ffffffff81560d14: gpiod_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ab80)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_gpio_gate_is_enabled
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8157ab80-ffffffff8157abd4: gpiod_get_value (STB_GLOBAL)
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
