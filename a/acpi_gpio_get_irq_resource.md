# Function: <code>acpi_gpio_get_irq_resource</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0475)
Location: drivers/gpio/gpiolib-acpi.c:168
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8149f6a0-ffffffff8149f6c6: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814deec5)
Location: drivers/gpio/gpiolib-acpi.c:111
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff814de140-ffffffff814de166: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150de45)
Location: drivers/gpio/gpiolib-acpi.c:130
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8150d360-ffffffff8150d384: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81522b05)
Location: drivers/gpio/gpiolib-acpi.c:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81522990-ffffffff815229b4: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551025)
Location: drivers/gpio/gpiolib-acpi.c:142
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81550eb0-ffffffff81550ed4: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815724e9)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81572350-ffffffff81572374: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81617775)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff816168b0-ffffffff816168d4: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e029)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8163d1e0-ffffffff8163d204: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81621b69)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81620d40-ffffffff81620d64: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81691499)
Location: drivers/gpio/gpiolib-acpi.c:182
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81690300-ffffffff81690324: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b09e4)
Location: drivers/gpio/gpiolib-acpi.c:179
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff817af6c0-ffffffff817af6ec: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca564)
Location: drivers/gpio/gpiolib-acpi.c:210
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff818c8d80-ffffffff818c8dac: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d604)
Location: drivers/gpio/gpiolib-acpi.c:212
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8190be30-ffffffff8190be5c: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81955334)
Location: drivers/gpio/gpiolib-acpi.c:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81953b50-ffffffff81953b7c: acpi_gpio_get_irq_resource (STB_GLOBAL)
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
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca200)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffff8000106c9f80-ffff8000106c9fdc: acpi_gpio_get_irq_resource (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567ca9)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81567b10-ffffffff81567b34: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81558af9)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81558960-ffffffff81558984: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81566819)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81566680-ffffffff815666a4: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_gpio_get_irq_resource(struct acpi_resource *ares, struct acpi_resource_gpio **agpio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81580739)
Location: drivers/gpio/gpiolib-acpi.c:154
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815805a0-ffffffff815805c4: acpi_gpio_get_irq_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
