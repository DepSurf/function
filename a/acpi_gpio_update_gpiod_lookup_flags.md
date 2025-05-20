# Function: <code>acpi_gpio_update_gpiod_lookup_flags</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81552216)
Location: drivers/gpio/gpiolib-acpi.c:536
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81552110-ffffffff8155213e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81573856)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81573750-ffffffff8157377e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81617f76)
Location: drivers/gpio/gpiolib-acpi.c:613
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81617e70-ffffffff81617e9e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e7dc)
Location: drivers/gpio/gpiolib-acpi.c:641
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff8163e890-ffffffff8163e8be: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff816221ec)
Location: drivers/gpio/gpiolib-acpi.c:641
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff816222a0-ffffffff816222ce: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81691928)
Location: drivers/gpio/gpiolib-acpi.c:695
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81691a20-ffffffff81691a4e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b0e36)
Location: drivers/gpio/gpiolib-acpi.c:680
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff817b0f30-ffffffff817b0f66: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca95d)
Location: drivers/gpio/gpiolib-acpi.c:717
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff818c9cc0-ffffffff818c9d0f: acpi_gpio_update_gpiod_lookup_flags.isra.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8190da40)
Location: drivers/gpio/gpiolib-acpi.c:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8190cd60-ffffffff8190cdad: acpi_gpio_update_gpiod_lookup_flags.isra.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-acpi.c (ffffffff819557a0)
Location: drivers/gpio/gpiolib-acpi.c:698
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81954a60-ffffffff81954aad: acpi_gpio_update_gpiod_lookup_flags.isra.0 (STB_LOCAL)
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
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb810)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffff8000106cb6b8-ffff8000106cb72c: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib-acpi.h:71
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81569016)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81568f10-ffffffff81568f3e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559e66)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81559d60-ffffffff81559d8e: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567b86)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff81567a80-ffffffff81567aae: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_gpio_update_gpiod_lookup_flags(long unsigned int *lookupflags, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81581aa6)
Location: drivers/gpio/gpiolib-acpi.c:606
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
**Symbols:**

```
ffffffff815819a0-ffffffff815819ce: acpi_gpio_update_gpiod_lookup_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
