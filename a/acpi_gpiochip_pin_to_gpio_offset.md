# Function: <code>acpi_gpiochip_pin_to_gpio_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_gpiochip_pin_to_gpio_offset(struct gpio_chip *chip, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814286b0)
Location: drivers/gpio/gpiolib-acpi.c:74
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
**Symbols:**

```
ffffffff814286b0-ffffffff8142873d: acpi_gpiochip_pin_to_gpio_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_gpiochip_pin_to_gpio_offset(struct gpio_device *gdev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814739a0)
Location: drivers/gpio/gpiolib-acpi.c:74
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814739a0-ffffffff81473a39: acpi_gpiochip_pin_to_gpio_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_gpiochip_pin_to_gpio_offset(struct gpio_device *gdev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81495bc0)
Location: drivers/gpio/gpiolib-acpi.c:75
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81495bc0-ffffffff81495c59: acpi_gpiochip_pin_to_gpio_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_gpiochip_pin_to_gpio_offset(struct gpio_device *gdev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149f5f0)
Location: drivers/gpio/gpiolib-acpi.c:75
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8149f5f0-ffffffff8149f68c: acpi_gpiochip_pin_to_gpio_offset (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_device *gdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
