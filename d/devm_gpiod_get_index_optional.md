# Function: <code>devm_gpiod_get_index_optional</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81423a70)
Location: drivers/gpio/devres.c:185
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff81423a70-ffffffff81423a97: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8146d0b6)
Location: drivers/gpio/devres.c:185
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff8146d080-ffffffff8146d0a7: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff8148ef86)
Location: drivers/gpio/devres.c:185
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff8148ef50-ffffffff8148ef77: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81498a26)
Location: drivers/gpio/devres.c:195
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff814989f0-ffffffff81498a15: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff814d6d16)
Location: drivers/gpio/devres.c:196
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff814d6ce0-ffffffff814d6d05: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81505e15)
Location: drivers/gpio/devres.c:238
Inline: True
Inline callers:
  - drivers/gpio/devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff81505de0-ffffffff81505e05: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81521145)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
```
**Symbols:**

```
ffffffff81521110-ffffffff81521135: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154f645)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8154f610-ffffffff8154f635: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81570c05)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81570bd0-ffffffff81570bf5: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81615585)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff816150b0-ffffffff816150d5: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81639828)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff816393a0-ffffffff816393c5: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d478)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff8161d000-ffffffff8161d022: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c928)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff8168c490-ffffffff8168c4b2: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9f58)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff817a9a00-ffffffff817a9a2e: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c2aa8)
Location: drivers/gpio/gpiolib-devres.c:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff818c24d0-ffffffff818c24fe: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff819059a8)
Location: drivers/gpio/gpiolib-devres.c:186
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff819053d0-ffffffff819053fe: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d3b8)
Location: drivers/gpio/gpiolib-devres.c:186
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_get_gpio_descs
```
**Symbols:**

```
ffffffff8194cde0-ffffffff8194ce0e: devm_gpiod_get_index_optional (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c6be4)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
**Symbols:**

```
ffff8000106c6b68-ffff8000106c6bc0: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0864608)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c08645bc-c08645f4: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0000000008434ec)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000843470-c0000000008434d0: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aa772)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe0004aa702-ffffffe0004aa754: devm_gpiod_get_index_optional (STB_GLOBAL)
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
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815663c5)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81566390-ffffffff815663b5: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81557215)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff815571e0-ffffffff81557205: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81564f35)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81564f00-ffffffff81564f25: devm_gpiod_get_index_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *devm_gpiod_get_index_optional(struct device *dev, const char *con_id, unsigned int index, enum gpiod_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157ee55)
Location: drivers/gpio/gpiolib-devres.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_optional
Direct callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff8157ee20-ffffffff8157ee45: devm_gpiod_get_index_optional (STB_GLOBAL)
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
