# Function: <code>gpiochip_add_data</code>

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
int gpiochip_add_data(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470710)
Location: drivers/gpio/gpiolib.c:1028
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff81470710-ffffffff81470e90: gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_add_data(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814927f0)
Location: drivers/gpio/gpiolib.c:1104
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff814927f0-ffffffff81492ff7: gpiochip_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_add_data(struct gpio_chip *chip, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149c1e0)
Location: drivers/gpio/gpiolib.c:1097
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpiolib.c:devm_gpiochip_add_data
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
**Symbols:**

```
ffffffff8149c1e0-ffffffff8149c9af: gpiochip_add_data (STB_GLOBAL)
```
</details>
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
