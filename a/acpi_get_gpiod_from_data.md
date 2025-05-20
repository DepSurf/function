# Function: <code>acpi_get_gpiod_from_data</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_from_data(struct fwnode_handle *fwnode, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818c9700)
Location: drivers/gpio/gpiolib-acpi.c:938
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff818c9700-ffffffff818c97b4: acpi_get_gpiod_from_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_from_data(struct fwnode_handle *fwnode, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190c7c0)
Location: drivers/gpio/gpiolib-acpi.c:940
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8190c7c0-ffffffff8190c874: acpi_get_gpiod_from_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_from_data(struct fwnode_handle *fwnode, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff819543b0)
Location: drivers/gpio/gpiolib-acpi.c:916
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff819543b0-ffffffff81954477: acpi_get_gpiod_from_data (STB_LOCAL)
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
