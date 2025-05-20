# Function: <code>dev_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: drivers/base/property.c:180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: drivers/base/property.c:185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: drivers/base/property.c:185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e5f15)
Location: drivers/base/property.c:183
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff815e5e00-ffffffff815e5e12: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d255)
Location: drivers/base/property.c:190
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff8164d100-ffffffff8164d112: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688e15)
Location: drivers/base/property.c:251
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816886e0-ffffffff816886f2: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8b15)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816a83d0-ffffffff816a83e2: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1bb5)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/devcon.c:device_fwnode_match
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816e1780-ffffffff816e1792: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705d65)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff81705930-ffffffff81705942: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0385)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817c01a0-ffffffff817c01b2: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5245)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817d5060-ffffffff817d5072: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8c85)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_bus_match
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff817b8a70-ffffffff817b8a82: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818428e5)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_bus_match
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:devprop_gpiochip_set_names
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/net/phy/phy_device.c:device_phy_find_device
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff81842700-ffffffff81842712: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986ae5)
Location: drivers/base/property.c:20
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_bus_match
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/regmap/regmap.c:regmap_get_val_endian
  - drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/net/phy/phy_device.c:device_phy_find_device
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/mmc/core/host.c:mmc_of_parse
  - drivers/hte/hte.c:hte_ts_get
  - net/ethernet/eth.c:device_get_ethdev_address
```
**Symbols:**

```
ffffffff819860f0-ffffffff81986108: dev_fwnode (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2908)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe
  - drivers/irqchip/irq-sni-exiu.c:exiu_acpi_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffff8000108f22c0-ffff8000108f2300: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df5b0)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
c09def48-c09def70: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c600)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
c00000000098bbe0-c00000000098bc08: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584476)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffe000583ef4-ffffffe000583f2c: dev_fwnode (STB_GLOBAL)
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
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb4b5)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816cb080-ffffffff816cb092: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a67e5)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
```
**Symbols:**

```
ffffffff816a63b0-ffffffff816a63c2: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9a25)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff816f95f0-ffffffff816f9602: dev_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *dev_fwnode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817142c5)
Location: drivers/base/property.c:21
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_u64_array
  - drivers/base/property.c:device_property_read_u32_array
  - drivers/base/property.c:device_property_read_u16_array
  - drivers/base/property.c:device_property_read_u8_array
  - drivers/base/property.c:device_property_present
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/core.c:device_match_fwnode
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/swnode.c:software_node_notify
  - drivers/mmc/core/host.c:mmc_of_parse
```
**Symbols:**

```
ffffffff81713e90-ffffffff81713ea2: dev_fwnode (STB_GLOBAL)
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
