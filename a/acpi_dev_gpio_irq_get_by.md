# Function: <code>acpi_dev_gpio_irq_get_by</code>

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
int acpi_dev_gpio_irq_get_by(struct acpi_device *adev, const char *name, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e6f0)
Location: drivers/gpio/gpiolib-acpi.c:965
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
ffffffff8163e6f0-ffffffff8163e888: acpi_dev_gpio_irq_get_by (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_dev_gpio_irq_get_by(struct acpi_device *adev, const char *name, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81622100)
Location: drivers/gpio/gpiolib-acpi.c:965
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
ffffffff81622100-ffffffff81622298: acpi_dev_gpio_irq_get_by (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_dev_gpio_irq_get_by(struct acpi_device *adev, const char *name, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1019
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
ffffffff81ce27c9-ffffffff81ce27dd: acpi_dev_gpio_irq_get_by.cold (STB_LOCAL)
ffffffff81691820-ffffffff81691a16: acpi_dev_gpio_irq_get_by (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_dev_gpio_irq_get_by(struct acpi_device *adev, const char *name, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:1004
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
ffffffff81ea919b-ffffffff81ea91bc: acpi_dev_gpio_irq_get_by.cold (STB_LOCAL)
ffffffff817b0cf0-ffffffff817b0f2e: acpi_dev_gpio_irq_get_by (STB_GLOBAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
