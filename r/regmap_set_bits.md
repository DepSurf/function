# Function: <code>regmap_set_bits</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff81640a89)
Location: include/linux/regmap.h:1178
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff8180ee50)
Location: include/linux/regmap.h:1178
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff81624054)
Location: include/linux/regmap.h:1178
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff817f3680)
Location: include/linux/regmap.h:1178
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_power_off
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff81693859)
Location: include/linux/regmap.h:1218
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff8187c5ba)
Location: include/linux/regmap.h:1218
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff817b44fe)
Location: include/linux/regmap.h:1243
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff819c4f84)
Location: include/linux/regmap.h:1243
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff818ce800)
Location: include/linux/regmap.h:1292
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81b3bff9)
Location: include/linux/regmap.h:1292
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff81911860)
Location: include/linux/regmap.h:1309
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f419)
Location: include/linux/regmap.h:1309
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-tps65910.c (ffffffff81959710)
Location: include/linux/regmap.h:1310
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_output
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81be3339)
Location: include/linux/regmap.h:1310
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
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
