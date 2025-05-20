# Function: <code>gpiod_get_raw_value_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425bc0)
Location: drivers/gpio/gpiolib.c:1661
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_regs
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81425bc0-ffffffff81425bd8: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f470)
Location: drivers/gpio/gpiolib.c:2672
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8146f470-ffffffff8146f4f7: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814917d0)
Location: drivers/gpio/gpiolib.c:2881
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff814917d0-ffffffff81491857: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b3e0)
Location: drivers/gpio/gpiolib.c:2888
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8149b3e0-ffffffff8149b479: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da280)
Location: drivers/gpio/gpiolib.c:3159
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff814da280-ffffffff814da319: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509060)
Location: drivers/gpio/gpiolib.c:3350
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff81509060-ffffffff81509088: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d700)
Location: drivers/gpio/gpiolib.c:3592
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff8151d700-ffffffff8151d728: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154b760)
Location: drivers/gpio/gpiolib.c:3681
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8154b760-ffffffff8154b78a: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c9f0)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8156c9f0-ffffffff8156ca1a: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4448
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
**Symbols:**

```
ffffffff8161478b-ffffffff816147ea: gpiod_get_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81610700-ffffffff8161074b: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3272
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
**Symbols:**

```
ffffffff81bf5fe1-ffffffff81bf6040: gpiod_get_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81636b00-ffffffff81636b4b: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3249
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
**Symbols:**

```
ffffffff81be7e32-ffffffff81be7e91: gpiod_get_raw_value_cansleep.cold (STB_LOCAL)
ffffffff8161a3c0-ffffffff8161a40b: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3308
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
**Symbols:**

```
ffffffff81ce1a11-ffffffff81ce1a70: gpiod_get_raw_value_cansleep.cold (STB_LOCAL)
ffffffff81689810-ffffffff8168985b: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3429
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
**Symbols:**

```
ffffffff81ea822f-ffffffff81ea828c: gpiod_get_raw_value_cansleep.cold (STB_LOCAL)
ffffffff817a66c0-ffffffff817a6715: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be600)
Location: drivers/gpio/gpiolib.c:3499
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff818be600-ffffffff818be69e: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901850)
Location: drivers/gpio/gpiolib.c:3540
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81901850-ffffffff819018ea: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949460)
Location: drivers/gpio/gpiolib.c:3733
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts_thread
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff81949460-ffffffff819494f2: gpiod_get_raw_value_cansleep (STB_GLOBAL)
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
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfd70)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffff8000106bfd70-ffff8000106bfdb8: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08605b4)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c08605b4-c08605ec: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083de70)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c00000000083de70-c00000000083ded4: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a728e)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffe0004a728e-ffffffe0004a72ce: gpiod_get_raw_value_cansleep (STB_GLOBAL)
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
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815621b0)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff815621b0-ffffffff815621da: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553000)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
**Symbols:**

```
ffffffff81553000-ffffffff8155302a: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560d20)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81560d20-ffffffff81560d4a: gpiod_get_raw_value_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_raw_value_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157abe0)
Location: drivers/gpio/gpiolib.c:4035
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8157abe0-ffffffff8157ac0a: gpiod_get_raw_value_cansleep (STB_GLOBAL)
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
