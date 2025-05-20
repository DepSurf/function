# Function: <code>device_set_node</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_set_node(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81832770)
Location: drivers/base/core.c:4798
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
```
**Symbols:**

```
ffffffff81832770-ffffffff8183278d: device_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_set_node(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81973eb0)
Location: drivers/base/core.c:4837
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81973eb0-ffffffff81973ed5: device_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_set_node(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81adf440)
Location: drivers/base/core.c:5056
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81adf440-ffffffff81adf465: device_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_set_node(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2d6e0)
Location: drivers/base/core.c:5065
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b2d6e0-ffffffff81b2d705: device_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_set_node(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b84ee0)
Location: drivers/base/core.c:5079
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81b84ee0-ffffffff81b84f05: device_set_node (STB_GLOBAL)
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
