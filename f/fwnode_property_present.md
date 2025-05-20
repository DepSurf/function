# Function: <code>fwnode_property_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551530)
Location: drivers/base/property.c:216
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff81551530-ffffffff81551561: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2dd0)
Location: drivers/base/property.c:221
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff815a2dd0-ffffffff815a2e22: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool fwnode_property_present(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d14e0)
Location: drivers/base/property.c:221
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff815d14e0-ffffffff815d1532: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6b50)
Location: drivers/base/property.c:252
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff815e6b50-ffffffff815e6bcc: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164df80)
Location: drivers/base/property.c:260
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff8164df80-ffffffff8164e001: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816896e0)
Location: drivers/base/property.c:321
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/acpi/property.c:acpi_graph_get_next_endpoint
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff816896e0-ffffffff8168975c: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8fa0)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
```
**Symbols:**

```
ffffffff816a8fa0-ffffffff816a9015: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2570)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
**Symbols:**

```
ffffffff816e2570-ffffffff816e25e5: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81706720)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81706720-ffffffff81706797: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c03c0)
Location: drivers/base/property.c:46
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
**Symbols:**

```
ffffffff817c03c0-ffffffff817c0437: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5280)
Location: drivers/base/property.c:46
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
**Symbols:**

```
ffffffff817d5280-ffffffff817d52f7: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8cc0)
Location: drivers/base/property.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
**Symbols:**

```
ffffffff817b8cc0-ffffffff817b8d37: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842920)
Location: drivers/base/property.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81842920-ffffffff81842997: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986110)
Location: drivers/base/property.c:45
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81986110-ffffffff8198619d: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af46c0)
Location: drivers/base/property.c:52
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81af46c0-ffffffff81af474d: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b428d0)
Location: drivers/base/property.c:56
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b428d0-ffffffff81b4295d: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9a7a0)
Location: drivers/base/property.c:56
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
  - drivers/base/property.c:device_property_present
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b9a7a0-ffffffff81b9a82d: fwnode_property_present (STB_GLOBAL)
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
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f36f8)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/base/property.c:device_property_present
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffff8000108f36f8-ffff8000108f3784: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09e0000)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/base/property.c:device_property_present
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_match
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
c09e0000-c09e008c: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d4b0)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/base/property.c:device_property_present
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
c00000000098d4b0-c00000000098d5c8: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584dfa)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffe000584dfa-ffffffe000584e50: fwnode_property_present (STB_GLOBAL)
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
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbe70)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816cbe70-ffffffff816cbee7: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a71a0)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816a71a0-ffffffff816a7217: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa3e0)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff816fa3e0-ffffffff816fa457: fwnode_property_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool fwnode_property_present(const struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714c80)
Location: drivers/base/property.c:46
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/base/property.c:device_property_present
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81714c80-ffffffff81714cf7: fwnode_property_present (STB_GLOBAL)
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
