# Function: <code>acpi_dev_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_dev_get_property(struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148a40c)
Location: drivers/acpi/property.c:394
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8148a40c-ffffffff8148a42e: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_dev_get_property(struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d91dd)
Location: drivers/acpi/property.c:394
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814d91dd-ffffffff814d91ff: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_dev_get_property(struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fb968)
Location: drivers/acpi/property.c:447
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814fb968-ffffffff814fb98a: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c4e5)
Location: drivers/acpi/property.c:463
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
```
**Symbols:**

```
ffffffff8150b1c0-ffffffff8150b1e2: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154f0e2)
Location: drivers/acpi/property.c:468
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
```
**Symbols:**

```
ffffffff8154dc50-ffffffff8154dc72: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8158597d)
Location: drivers/acpi/property.c:468
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
```
**Symbols:**

```
ffffffff81584700-ffffffff81584722: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159deae)
Location: drivers/acpi/property.c:524
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
```
**Symbols:**

```
ffffffff8159c880-ffffffff8159c8a2: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815cf3ac)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815cdef0-ffffffff815cdf12: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815f062c)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815ef170-ffffffff815ef192: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169c8ca)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff8169b3b0-ffffffff8169b3d2: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b9764)
Location: drivers/acpi/property.c:531
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff816b81f0-ffffffff816b8212: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b725)
Location: drivers/acpi/property.c:531
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff8169a190-ffffffff8169a1b2: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff817115c5)
Location: drivers/acpi/property.c:531
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff81710090-ffffffff817100b2: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff818405e1)
Location: drivers/acpi/property.c:537
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff8183ebe0-ffffffff8183ec1a: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81976f72)
Location: drivers/acpi/property.c:696
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff81974a00-ffffffff81974a3a: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bd872)
Location: drivers/acpi/property.c:696
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff819bb220-ffffffff819bb25a: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a08142)
Location: drivers/acpi/property.c:700
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
  - drivers/spi/spi.c:acpi_spi_parse_apple_properties
```
**Symbols:**

```
ffffffff81a05a50-ffffffff81a05a8a: acpi_dev_get_property (STB_GLOBAL)
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
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077b608)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff800010779a90-ffff800010779ae8: acpi_dev_get_property (STB_GLOBAL)
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
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815df2bc)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815dde00-ffffffff815dde22: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ca8fc)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815c9440-ffffffff815c9462: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e490c)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815e3450-ffffffff815e3472: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_property(const struct acpi_device *adev, const char *name, acpi_object_type type, const union acpi_object **obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fe7cc)
Location: drivers/acpi/property.c:528
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_init_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815fd310-ffffffff815fd332: acpi_dev_get_property (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device *adev</code> ➡️ <code>const struct acpi_device *adev</code>
</li>
</ul>
</details>
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
