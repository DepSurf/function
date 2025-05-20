# Function: <code>is_acpi_data_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814294c3)
Location: include/acpi/acpi_bus.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:410
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474891)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:412
Inline: True
```
```
In drivers/base/property.c (ffffffff815a32e8)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496d61)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:412
Inline: True
```
```
In drivers/base/property.c (ffffffff815d19f8)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_named_child_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0a00)
Location: include/acpi/acpi_bus.h:415
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
```
In drivers/acpi/property.c (ffffffff8150b438)
Location: include/acpi/acpi_bus.h:415
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e328)
Location: drivers/acpi/property.c:1306
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff8154dcb0-ffffffff8154dcd8: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81584818)
Location: drivers/acpi/property.c:1314
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff815845f0-ffffffff81584618: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159cb45)
Location: drivers/acpi/property.c:1355
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff8159c760-ffffffff8159c788: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce5fc)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815cdbd0-ffffffff815cdbf8: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef87c)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815eee50-ffffffff815eee78: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169bc66)
Location: drivers/acpi/property.c:1429
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff8169b090-ffffffff8169b0b8: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8a86)
Location: drivers/acpi/property.c:1444
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff816b7ed0-ffffffff816b7ef8: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169aa26)
Location: drivers/acpi/property.c:1423
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff81699e80-ffffffff81699ea8: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710886)
Location: drivers/acpi/property.c:1418
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff8170fd20-ffffffff8170fd48: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff818400d5)
Location: drivers/acpi/property.c:1455
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff8183e8c0-ffffffff8183e8f4: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819766d5)
Location: drivers/acpi/property.c:1626
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81974890-ffffffff819748c4: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc8b5)
Location: drivers/acpi/property.c:1614
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff819bb0b0-ffffffff819bb0e4: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a071a5)
Location: drivers/acpi/property.c:1682
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81a058e0-ffffffff81a05914: is_acpi_data_node (STB_GLOBAL)
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
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a628)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_translate
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffff800010779b40-ffff800010779b98: is_acpi_data_node (STB_GLOBAL)
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
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de50c)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815ddae0-ffffffff815ddb08: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c9b4c)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff815c9120-ffffffff815c9148: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e3b5c)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815e3130-ffffffff815e3158: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fda1c)
Location: drivers/acpi/property.c:1381
Inline: True
Inline callers:
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffff815fcff0-ffffffff815fd018: is_acpi_data_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
