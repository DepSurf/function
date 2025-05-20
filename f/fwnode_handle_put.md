# Function: <code>fwnode_handle_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81550f10)
Location: drivers/base/property.c:879
Inline: False
```
**Symbols:**

```
ffffffff81550f10-ffffffff81550f1b: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2d10)
Location: drivers/base/property.c:926
Inline: False
```
**Symbols:**

```
ffffffff815a2d10-ffffffff815a2d1b: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1420)
Location: drivers/base/property.c:926
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
**Symbols:**

```
ffffffff815d1420-ffffffff815d142b: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6092)
Location: drivers/base/property.c:1018
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
**Symbols:**

```
ffffffff815e5f80-ffffffff815e5fa6: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d3e5)
Location: drivers/base/property.c:1067
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
**Symbols:**

```
ffffffff8164d2c0-ffffffff8164d2e9: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688d55)
Location: drivers/base/property.c:1153
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
**Symbols:**

```
ffffffff81688be0-ffffffff81688c08: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8a55)
Location: drivers/base/property.c:676
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
**Symbols:**

```
ffffffff816a88e0-ffffffff816a8908: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2413)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/devcon.c:device_connection_find_match
  - drivers/base/devcon.c:device_connection_find_match
```
**Symbols:**

```
ffffffff816e19d0-ffffffff816e19f8: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817065c3)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff81705b80-ffffffff81705ba8: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c137a)
Location: drivers/base/property.c:779
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - lib/vsprintf.c:fwnode_full_name_string
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817c02f0-ffffffff817c0318: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d6517)
Location: drivers/base/property.c:831
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - lib/vsprintf.c:fwnode_full_name_string
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817d51b0-ffffffff817d51d8: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9f7b)
Location: drivers/base/property.c:831
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - lib/vsprintf.c:fwnode_full_name_string
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
```
**Symbols:**

```
ffffffff817b8bc0-ffffffff817b8be8: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843c0c)
Location: drivers/base/property.c:826
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_connection_find_match
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_node
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_get_nth_parent
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - lib/vsprintf.c:fwnode_full_name_string
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81842850-ffffffff81842878: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986fea)
Location: drivers/base/property.c:826
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - lib/vsprintf.c:fwnode_full_name_string
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
**Symbols:**

```
ffffffff81986c90-ffffffff81986cd1: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af582a)
Location: drivers/base/property.c:834
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/phy_device.c:phy_device_release
  - drivers/net/phy/mdio_device.c:mdio_device_release
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81af5440-ffffffff81af5481: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43a5a)
Location: drivers/base/property.c:870
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/net/phy/phy_device.c:phy_device_release
  - drivers/net/phy/mdio_device.c:mdio_device_release
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b43670-ffffffff81b436b1: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9baaa)
Location: drivers/base/property.c:934
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-swnode.c:swnode_gpio_count
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/property.c:acpi_fwnode_get_name_prefix
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_deinit_device
  - drivers/iommu/iommu.c:iommu_init_device
  - drivers/iommu/iommu.c:remove_iommu_group
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
  - drivers/gpu/drm/drm_bridge_connector.c:drm_bridge_connector_destroy
  - drivers/net/phy/phy_device.c:phy_device_release
  - drivers/net/phy/mdio_bus.c:mdiobus_release
  - drivers/net/phy/mdio_device.c:mdio_device_release
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/usb/roles/class.c:usb_role_switch_is_parent
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - lib/vsprintf.c:fwnode_full_name_string
```
**Symbols:**

```
ffffffff81b9b5e0-ffffffff81b9b621: fwnode_handle_put (STB_GLOBAL)
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
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3590)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffff8000108f2680-ffff8000108f26c0: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09dfe88)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c09df2a8-c09df2e4: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d268)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
c00000000098c120-c00000000098c17c: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584d14)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffe0005841fa-ffffffe000584228: fwnode_handle_put (STB_GLOBAL)
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
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbd13)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816cb2d0-ffffffff816cb2f8: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a7043)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816a6600-ffffffff816a6628: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa283)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff816f9840-ffffffff816f9868: fwnode_handle_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fwnode_handle_put(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714b23)
Location: drivers/base/property.c:700
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_get_next_parent
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
  - drivers/base/devcon.c:fwnode_connection_find_match
```
**Symbols:**

```
ffffffff817140e0-ffffffff81714108: fwnode_handle_put (STB_GLOBAL)
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
