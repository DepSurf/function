# Function: <code>is_acpi_node</code>

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
In drivers/gpio/gpiolib.c (ffffffff81426d19)
Location: include/acpi/acpi_bus.h:393
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/base/property.c (ffffffff81551015)
Location: include/acpi/acpi_bus.h:393
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
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
In drivers/gpio/gpiolib.c (ffffffff814710db)
Location: include/acpi/acpi_bus.h:395
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/base/property.c (ffffffff815a2fe5)
Location: include/acpi/acpi_bus.h:395
Inline: True
Inline callers:
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:__fwnode_property_present
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
In drivers/gpio/gpiolib.c (ffffffff8149324b)
Location: include/acpi/acpi_bus.h:395
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/base/property.c (ffffffff815d16f5)
Location: include/acpi/acpi_bus.h:395
Inline: True
Inline callers:
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:__fwnode_property_present
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149e104)
Location: include/acpi/acpi_bus.h:398
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
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
In drivers/gpio/gpiolib.c (ffffffff814dcc60)
Location: include/acpi/acpi_bus.h:406
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
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
In drivers/gpio/gpiolib.c (ffffffff8150b060)
Location: include/acpi/acpi_bus.h:409
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
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
In drivers/gpio/gpiolib.c (ffffffff8151feb0)
Location: include/acpi/acpi_bus.h:415
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
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
In drivers/gpio/gpiolib.c (ffffffff8154e017)
Location: include/acpi/acpi_bus.h:402
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff81555eab)
Location: include/acpi/acpi_bus.h:402
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff8156f217)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff815774eb)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff81613717)
Location: include/acpi/acpi_bus.h:400
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff8161c45b)
Location: include/acpi/acpi_bus.h:400
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff816385f7)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff81642c2b)
Location: include/acpi/acpi_bus.h:401
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff8161c12b)
Location: include/acpi/acpi_bus.h:402
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/pwm/core.c (ffffffff81625a4b)
Location: include/acpi/acpi_bus.h:402
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff8168b64b)
Location: include/acpi/acpi_bus.h:408
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/pwm/core.c (ffffffff81694f25)
Location: include/acpi/acpi_bus.h:408
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81905894)
Location: include/acpi/acpi_bus.h:408
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff8190b971)
Location: include/acpi/acpi_bus.h:408
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
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
In drivers/gpio/gpiolib.c (ffffffff817a89ba)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/pwm/core.c (ffffffff817b5b75)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81a585d3)
Location: include/acpi/acpi_bus.h:412
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81a5f298)
Location: include/acpi/acpi_bus.h:412
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
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
In drivers/gpio/gpiolib.c (ffffffff818bc814)
Location: include/acpi/acpi_bus.h:410
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
```
In drivers/pwm/core.c (ffffffff818cff35)
Location: include/acpi/acpi_bus.h:410
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81be2483)
Location: include/acpi/acpi_bus.h:410
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81bea638)
Location: include/acpi/acpi_bus.h:410
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
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
In drivers/gpio/gpiolib.c (ffffffff818ff984)
Location: include/acpi/acpi_bus.h:413
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
```
In drivers/pwm/core.c (ffffffff81912eb5)
Location: include/acpi/acpi_bus.h:413
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81c39d53)
Location: include/acpi/acpi_bus.h:413
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81c42a68)
Location: include/acpi/acpi_bus.h:413
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
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
In drivers/gpio/gpiolib.c (ffffffff81947204)
Location: include/acpi/acpi_bus.h:508
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
```
In drivers/pwm/core.c (ffffffff8195adf5)
Location: include/acpi/acpi_bus.h:508
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81cef0d3)
Location: include/acpi/acpi_bus.h:508
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81cf8128)
Location: include/acpi/acpi_bus.h:508
Inline: True
Inline callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
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
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067bc0c)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_translate
```
```
In drivers/gpio/gpiolib.c (ffff8000106c52ac)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffff8000106d8bc4)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:689
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/acpi.h:689
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:689
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/acpi.h:689
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:689
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/acpi.h:689
Inline: True
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
In drivers/gpio/gpiolib.c (ffffffff815649d7)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff8156c2fb)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81555827)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
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
In drivers/gpio/gpiolib.c (ffffffff81563547)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff8156b23b)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/gpio/gpiolib.c (ffffffff8157d467)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
```
```
In drivers/pwm/core.c (ffffffff8158573b)
Location: include/acpi/acpi_bus.h:399
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:pwm_get
```
</details>
</li>
</ul>

## Differences
