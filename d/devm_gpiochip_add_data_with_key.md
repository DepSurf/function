# Function: <code>devm_gpiochip_add_data_with_key</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff816153a0)
Location: drivers/gpio/gpiolib-devres.c:506
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
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
ffffffff816153a0-ffffffff81615446: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff816397c0)
Location: drivers/gpio/gpiolib-devres.c:504
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
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
ffffffff816397c0-ffffffff8163981a: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d410)
Location: drivers/gpio/gpiolib-devres.c:504
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8161d410-ffffffff8161d46a: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c8c0)
Location: drivers/gpio/gpiolib-devres.c:504
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8168c8c0-ffffffff8168c91a: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9ee0)
Location: drivers/gpio/gpiolib-devres.c:504
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff817a9ee0-ffffffff817a9f47: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c2a20)
Location: drivers/gpio/gpiolib-devres.c:472
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff818c2a20-ffffffff818c2a87: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81905920)
Location: drivers/gpio/gpiolib-devres.c:417
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81905920-ffffffff8190598e: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int devm_gpiochip_add_data_with_key(struct device *dev, struct gpio_chip *gc, void *data, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d330)
Location: drivers/gpio/gpiolib-devres.c:417
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff8194d330-ffffffff8194d39e: devm_gpiochip_add_data_with_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
