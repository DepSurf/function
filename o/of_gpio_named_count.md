# Function: <code>of_gpio_named_count</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c8200)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpio_get_count
  - drivers/gpio/gpiolib-of.c:of_gpio_spi_cs_get_count
```
```
In drivers/spi/spi.c (ffff8000109c7c24)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0865818)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpio_get_count
  - drivers/gpio/gpiolib-of.c:of_gpio_spi_cs_get_count
```
```
In drivers/spi/spi.c (c0ab098c)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c00000000084575c)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpio_get_count
  - drivers/gpio/gpiolib-of.c:of_gpio_spi_cs_get_count
```
```
In drivers/spi/spi.c (c000000000a88720)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab9f2)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpio_get_count
  - drivers/gpio/gpiolib-of.c:of_gpio_spi_cs_get_count
```
```
In drivers/spi/spi.c (ffffffe000618356)
Location: include/linux/of_gpio.h:98
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
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
