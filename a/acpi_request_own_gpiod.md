# Function: <code>acpi_request_own_gpiod</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163df70)
Location: drivers/gpio/gpiolib-acpi.c:248
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8163df70-ffffffff8163e000: acpi_request_own_gpiod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81621ab0)
Location: drivers/gpio/gpiolib-acpi.c:248
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81621ab0-ffffffff81621b3f: acpi_request_own_gpiod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:299
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff816910f0-ffffffff8169118d: acpi_request_own_gpiod (STB_LOCAL)
ffffffff81ce26f1-ffffffff81ce270c: acpi_request_own_gpiod.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:295
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff817b0620-ffffffff817b06cc: acpi_request_own_gpiod (STB_LOCAL)
ffffffff81ea90c6-ffffffff81ea90e1: acpi_request_own_gpiod.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca150)
Location: drivers/gpio/gpiolib-acpi.c:326
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff818ca150-ffffffff818ca229: acpi_request_own_gpiod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d1f0)
Location: drivers/gpio/gpiolib-acpi.c:328
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8190d1f0-ffffffff8190d2c7: acpi_request_own_gpiod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *acpi_request_own_gpiod(struct gpio_chip *chip, struct acpi_resource_gpio *agpio, unsigned int index, const char *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954ef0)
Location: drivers/gpio/gpiolib-acpi.c:304
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81954ef0-ffffffff81954fc7: acpi_request_own_gpiod (STB_LOCAL)
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
