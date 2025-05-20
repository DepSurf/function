# Function: <code>fwnode_property_read_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_string(struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551640)
Location: drivers/base/property.c:618
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
```
**Symbols:**

```
ffffffff81551640-ffffffff81551683: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_string(struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a30a0)
Location: drivers/base/property.c:626
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
```
**Symbols:**

```
ffffffff815a30a0-ffffffff815a30fa: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_string(struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d17b0)
Location: drivers/base/property.c:626
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
```
**Symbols:**

```
ffffffff815d17b0-ffffffff815d180a: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6936)
Location: drivers/base/property.c:606
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815e6420-ffffffff815e643f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164dd56)
Location: drivers/base/property.c:615
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff8164d790-ffffffff8164d7af: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689074)
Location: drivers/base/property.c:676
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff81688a20-ffffffff81688a3f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8d44)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff816a8710-ffffffff816a872f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2174)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff816e1f10-ffffffff816e1f2f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706324)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff817060c0-ffffffff817060df: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0904)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
**Symbols:**

```
ffffffff817c0730-ffffffff817c074f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d57a4)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817d55f0-ffffffff817d560f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b91e4)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff817b9030-ffffffff817b904c: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842e44)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/leds/led-core.c:led_init_default_state_get
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81842c90-ffffffff81842cac: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986b7a)
Location: drivers/base/property.c:435
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_init_default_state_get
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81986590-ffffffff819865b8: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af52fa)
Location: drivers/base/property.c:442
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_init_default_state_get
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81af4c10-ffffffff81af4c38: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b4352a)
Location: drivers/base/property.c:446
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_init_default_state_get
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b42e20-ffffffff81b42e48: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b49a)
Location: drivers/base/property.c:446
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_property_string
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/net/phy/phy_device.c:fwnode_get_phy_id
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_init_default_state_get
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b9acf0-ffffffff81b9ad18: fwnode_property_read_string (STB_GLOBAL)
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
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3174)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffff8000108f2ec8-ffff8000108f2f18: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfb38)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
c09df9d4-c09df9f8: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cdbc)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
c00000000098cb10-c00000000098cb54: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584a6a)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffe000584860-ffffffe0005848a8: fwnode_property_read_string (STB_GLOBAL)
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
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cba74)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816cb810-ffffffff816cb82f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6da4)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816a6b40-ffffffff816a6b5f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9fe4)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816f9d80-ffffffff816f9d9f: fwnode_property_read_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_string(const struct fwnode_handle *fwnode, const char *propname, const char **val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714884)
Location: drivers/base/property.c:401
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:device_property_read_string
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81714620-ffffffff8171463f: fwnode_property_read_string (STB_GLOBAL)
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
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
