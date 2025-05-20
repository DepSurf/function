# Function: <code>fwnode_property_read_u32</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150b52b)
Location: include/linux/property.h:150
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e42b)
Location: include/linux/property.h:156
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8158491b)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159ca12)
Location: include/linux/property.h:164
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce402)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c3011)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef682)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff818e41e4)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b892)
Location: include/linux/property.h:191
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff819b70af)
Location: include/linux/property.h:191
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b86b2)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff819b958f)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a652)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81707bdb)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/leds/led-core.c (ffffffff8199dd7f)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff817104b2)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff817834ab)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff8190b853)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
```
In drivers/leds/led-core.c (ffffffff81a4a89f)
Location: include/linux/property.h:200
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183ee52)
Location: include/linux/property.h:206
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818ba0cb)
Location: include/linux/property.h:206
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_cfg_init
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81a5f109)
Location: include/linux/property.h:206
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b3fd0f)
Location: include/linux/property.h:206
Inline: True
Inline callers:
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
```
```
In drivers/leds/led-core.c (ffffffff81bb8df4)
Location: include/linux/property.h:206
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975602)
Location: include/linux/property.h:220
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a08afb)
Location: include/linux/property.h:220
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81bea499)
Location: include/linux/property.h:220
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd629f)
Location: include/linux/property.h:220
Inline: True
Inline callers:
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
```
```
In drivers/leds/led-core.c (ffffffff81d5e05b)
Location: include/linux/property.h:220
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bbe72)
Location: include/linux/property.h:231
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a5197b)
Location: include/linux/property.h:231
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81c428c9)
Location: include/linux/property.h:231
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3e2b2)
Location: include/linux/property.h:231
Inline: True
Inline callers:
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
```
```
In drivers/leds/led-core.c (ffffffff81dc8c3b)
Location: include/linux/property.h:231
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/mipi-disco-img.c (ffffffff819f30ef)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
```
```
In drivers/acpi/property.c (ffffffff81a06722)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d6cb)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_parse_dt
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81cf7f89)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df4c02)
Location: include/linux/property.h:271
Inline: True
Inline callers:
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
```
```
In drivers/leds/led-core.c (ffffffff81e816fb)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_parse_fwnode_props
  - drivers/leds/led-core.c:led_parse_fwnode_props
```
```
In drivers/leds/led-class.c (ffffffff81e82bc4)
Location: include/linux/property.h:271
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/leds/led-class.c:led_classdev_register_ext
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a3b0)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffff800010b48874)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
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
In drivers/leds/led-core.c (c0c321b0)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
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
In drivers/leds/led-core.c (c000000000c3cf80)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
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
In drivers/leds/led-core.c (ffffffe00071c54a)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de312)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff81887ba4)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9952)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff8183f524)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3962)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff818d9044)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd822)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint
  - drivers/acpi/property.c:acpi_graph_get_child_prop_value
```
```
In drivers/leds/led-core.c (ffffffff818f5b64)
Location: include/linux/property.h:186
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
</ul>

## Differences
