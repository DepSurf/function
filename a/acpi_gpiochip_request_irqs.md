# Function: <code>acpi_gpiochip_request_irqs</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81523626)
Location: drivers/gpio/gpiolib-acpi.c:179
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551ae6)
Location: drivers/gpio/gpiolib-acpi.c:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81573166)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip *acpi_gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81617aac)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
```
**Symbols:**

```
ffffffff8161860c-ffffffff81618642: acpi_gpiochip_request_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip *acpi_gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e61c)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
```
**Symbols:**

```
ffffffff81bf68ec-ffffffff81bf6922: acpi_gpiochip_request_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip *acpi_gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81620fb0-ffffffff8162106a: acpi_gpiochip_request_irqs (STB_LOCAL)
ffffffff81be8819-ffffffff81be8835: acpi_gpiochip_request_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip *acpi_gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:251
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81690670-ffffffff81690745: acpi_gpiochip_request_irqs (STB_LOCAL)
ffffffff81ce2610-ffffffff81ce2641: acpi_gpiochip_request_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_request_irqs(struct acpi_gpio_chip *acpi_gpio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:247
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff817b0340-ffffffff817b0431: acpi_gpiochip_request_irqs (STB_LOCAL)
ffffffff81ea9086-ffffffff81ea90b2: acpi_gpiochip_request_irqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff83edbb96)
Location: drivers/gpio/gpiolib-acpi.c:278
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff837016b6)
Location: drivers/gpio/gpiolib-acpi.c:280
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff83934ef6)
Location: drivers/gpio/gpiolib-acpi.c:256
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106caff8)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568926)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559776)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567496)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815813b6)
Location: drivers/gpio/gpiolib-acpi.c:200
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
</details>
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
</ul>
