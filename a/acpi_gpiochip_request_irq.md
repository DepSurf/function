# Function: <code>acpi_gpiochip_request_irq</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81523410)
Location: drivers/gpio/gpiolib-acpi.c:153
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81523410-ffffffff815234b0: acpi_gpiochip_request_irq.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:159
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff815518c0-ffffffff81551962: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff81552b5c-ffffffff81552b79: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81572f40-ffffffff81572fe2: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8157415f-ffffffff8157417c: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_request_irq(struct acpi_gpio_chip *acpi_gpio, struct acpi_gpio_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81616b20-ffffffff81616bc2: acpi_gpiochip_request_irq (STB_LOCAL)
ffffffff816185ee-ffffffff8161860c: acpi_gpiochip_request_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_gpiochip_request_irq(struct acpi_gpio_chip *acpi_gpio, struct acpi_gpio_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff8163d450-ffffffff8163d4f5: acpi_gpiochip_request_irq (STB_LOCAL)
ffffffff81bf68ce-ffffffff81bf68ec: acpi_gpiochip_request_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81620ff0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff816906b6)
Location: drivers/gpio/gpiolib-acpi.c:222
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b0386)
Location: drivers/gpio/gpiolib-acpi.c:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:250
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff818c9e10-ffffffff818c9ef6: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8208e8cc-ffffffff8208e8e1: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:252
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff8190cea0-ffffffff8190cf86: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8210ebca-ffffffff8210ebdf: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:228
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81954ba0-ffffffff81954c86: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff821ec806-ffffffff821ec81b: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cad90)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffff8000106cad90-ffff8000106cae6c: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81568700-ffffffff815687a2: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8156991f-ffffffff8156993c: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81559550-ffffffff815595f2: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8155a76f-ffffffff8155a78c: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81567270-ffffffff81567312: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff8156848f-ffffffff815684ac: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:171
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_handle_deferred_request_irqs
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
```
**Symbols:**

```
ffffffff81581190-ffffffff81581232: acpi_gpiochip_request_irq.isra.0 (STB_LOCAL)
ffffffff815823af-ffffffff815823cc: acpi_gpiochip_request_irq.isra.0.cold (STB_LOCAL)
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
</ul>
