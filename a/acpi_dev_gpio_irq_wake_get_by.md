# Function: <code>acpi_dev_gpio_irq_wake_get_by</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device *adev, const char *name, int index, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1049
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
```
**Symbols:**

```
ffffffff8208e925-ffffffff8208e95a: acpi_dev_gpio_irq_wake_get_by.cold (STB_LOCAL)
ffffffff818ca810-ffffffff818caa8e: acpi_dev_gpio_irq_wake_get_by (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device *adev, const char *name, int index, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1051
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
```
**Symbols:**

```
ffffffff8210ec23-ffffffff8210ec4c: acpi_dev_gpio_irq_wake_get_by.cold (STB_LOCAL)
ffffffff8190d8b0-ffffffff8190db9c: acpi_dev_gpio_irq_wake_get_by (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device *adev, const char *name, int index, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1028
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
```
**Symbols:**

```
ffffffff821ec85f-ffffffff821ec888: acpi_dev_gpio_irq_wake_get_by.cold (STB_LOCAL)
ffffffff81955610-ffffffff819558fc: acpi_dev_gpio_irq_wake_get_by (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
