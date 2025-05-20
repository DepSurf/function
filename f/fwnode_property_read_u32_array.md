# Function: <code>fwnode_property_read_u32_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_u32_array(struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551d60)
Location: drivers/base/property.c:502
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u32_array
```
**Symbols:**

```
ffffffff81551d60-ffffffff81551eb8: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_u32_array(struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a38f0)
Location: drivers/base/property.c:509
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_u32_array
```
**Symbols:**

```
ffffffff815a38f0-ffffffff815a3a68: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_u32_array(struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d2000)
Location: drivers/base/property.c:509
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_property_read_u32_array
```
**Symbols:**

```
ffffffff815d2000-ffffffff815d2178: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e62c6)
Location: drivers/base/property.c:522
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
**Symbols:**

```
ffffffff815e62a0-ffffffff815e62bb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d636)
Location: drivers/base/property.c:531
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
**Symbols:**

```
ffffffff8164d610-ffffffff8164d62b: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688835)
Location: drivers/base/property.c:592
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
**Symbols:**

```
ffffffff816888d0-ffffffff816888eb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8525)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
**Symbols:**

```
ffffffff816a85c0-ffffffff816a85db: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1dc5)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
**Symbols:**

```
ffffffff816e1da0-ffffffff816e1dbb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705f75)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff81705f50-ffffffff81705f6b: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c05e5)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff817c05c0-ffffffff817c05db: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d54b0)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff817d5480-ffffffff817d549b: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8ef0)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff817b8ec0-ffffffff817b8edb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842b50)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff81842b20-ffffffff81842b3b: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff819863e0)
Location: drivers/base/property.c:343
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff819863a0-ffffffff819863ca: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4a10)
Location: drivers/base/property.c:350
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff81af49c0-ffffffff81af49ea: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42c20)
Location: drivers/base/property.c:354
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff81b42bd0-ffffffff81b42bfa: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9aaf0)
Location: drivers/base/property.c:354
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b9aaa0-ffffffff81b9aaca: fwnode_property_read_u32_array (STB_GLOBAL)
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
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2ca4)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_enable_quirk_socionext_synquacer
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffff8000108f2c20-ffff8000108f2c70: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df878)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
c09df81c-c09df850: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c908)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
c00000000098c8b0-c00000000098c8d4: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe0005846c4)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffe000584654-ffffffe000584698: fwnode_property_read_u32_array (STB_GLOBAL)
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
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb6c5)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff816cb6a0-ffffffff816cb6bb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a69f5)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff816a69d0-ffffffff816a69eb: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9c35)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff816f9c10-ffffffff816f9c2b: fwnode_property_read_u32_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fwnode_property_read_u32_array(const struct fwnode_handle *fwnode, const char *propname, u32 *val, size_t nval);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817144d5)
Location: drivers/base/property.c:317
Inline: True
Inline callers:
  - drivers/base/property.c:device_property_read_u32_array
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_get_default_pattern
  - drivers/leds/led-core.c:led_get_default_pattern
```
**Symbols:**

```
ffffffff817144b0-ffffffff817144cb: fwnode_property_read_u32_array (STB_GLOBAL)
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
