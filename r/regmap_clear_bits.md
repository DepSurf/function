# Function: <code>regmap_clear_bits</code>

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
In drivers/gpio/gpio-tps65910.c (ffffffff81640911)
Location: include/linux/regmap.h:1185
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff8180eea6)
Location: include/linux/regmap.h:1185
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff81623ee1)
Location: include/linux/regmap.h:1185
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff817f36d6)
Location: include/linux/regmap.h:1185
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81c05eb8)
Location: include/linux/regmap.h:1185
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff816936c1)
Location: include/linux/regmap.h:1225
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff8187c610)
Location: include/linux/regmap.h:1225
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81d09380)
Location: include/linux/regmap.h:1225
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff817b4331)
Location: include/linux/regmap.h:1250
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff819c4ff5)
Location: include/linux/regmap.h:1250
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81ed17ae)
Location: include/linux/regmap.h:1250
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff818ce601)
Location: include/linux/regmap.h:1299
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81b3bf88)
Location: include/linux/regmap.h:1299
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b44bb3)
Location: include/linux/regmap.h:1299
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff81911661)
Location: include/linux/regmap.h:1316
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f391)
Location: include/linux/regmap.h:1316
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b97f07)
Location: include/linux/regmap.h:1316
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
In drivers/gpio/gpio-tps65910.c (ffffffff81959511)
Location: include/linux/regmap.h:1317
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_input
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_set
```
```
In drivers/mfd/tps65910.c (ffffffff81be32b1)
Location: include/linux/regmap.h:1317
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81bebed7)
Location: include/linux/regmap.h:1317
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
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
