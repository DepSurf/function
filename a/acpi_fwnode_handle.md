# Function: <code>acpi_fwnode_handle</code>

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
In drivers/gpio/gpiolib-acpi.c (ffffffff814292ea)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_by_index
```
```
In drivers/acpi/glue.c (ffffffff8147f34f)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff814852d8)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff814883ee)
Location: include/acpi/acpi_bus.h:421
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:421
Inline: True
```
```
In drivers/acpi/container.c (ffffffff814afa19)
Location: include/acpi/acpi_bus.h:421
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81fa3f83)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/mfd/mfd-core.c (ffffffff8158ab71)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff815e18f5)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
```
```
In drivers/spi/spi.c (ffffffff815e92f0)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_spi_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8167cc72)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816cad2f)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff816f8f96)
Location: include/acpi/acpi_bus.h:421
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff814746a2)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_by_index
```
```
In drivers/acpi/glue.c (ffffffff814cdb06)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff814d3e62)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff814d7272)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/acpi/container.c (ffffffff814ff346)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81fd050e)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/mfd/mfd-core.c (ffffffff815dfd1e)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8163b788)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff816478be)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816da8cf)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172dce6)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff8175dcb4)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff814961d2)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_by_index
```
```
In drivers/acpi/glue.c (ffffffff814ef9d5)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff814f64b1)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff814f994d)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/acpi/container.c (ffffffff81522040)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8200dbc5)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c9be)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8166c808)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff816789ae)
Location: include/acpi/acpi_bus.h:430
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170a5af)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760ca6)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff8178a1e4)
Location: include/acpi/acpi_bus.h:430
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8149fd2c)
Location: include/acpi/acpi_bus.h:433
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff814fcad3)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff81504aba)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff81508a2f)
Location: include/acpi/acpi_bus.h:433
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8150c804)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
```
In drivers/acpi/container.c (ffffffff81533b31)
Location: include/acpi/acpi_bus.h:433
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff820ef618)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/base/property.c (ffffffff815e64c3)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff81620afa)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff81680e2f)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff8168d2be)
Location: include/acpi/acpi_bus.h:433
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81723f91)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817276fb)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f4df)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff817a9324)
Location: include/acpi/acpi_bus.h:433
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de7cc)
Location: include/acpi/acpi_bus.h:444
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff8153e993)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff81546dda)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff8154ae0f)
Location: include/acpi/acpi_bus.h:444
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8154e1f7)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_node_get_parent
```
```
In drivers/acpi/container.c (ffffffff815952b1)
Location: include/acpi/acpi_bus.h:444
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff826f8e06)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81609d85)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff8164dc94)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff81689183)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff816ea670)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff816f6cd9)
Location: include/acpi/acpi_bus.h:444
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817953f8)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798beb)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5a90)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff818207d4)
Location: include/acpi/acpi_bus.h:444
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150dabd)
Location: include/acpi/acpi_bus.h:447
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815748ca)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff8157ce7a)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff815814a4)
Location: include/acpi/acpi_bus.h:447
Inline: True
```
```
In drivers/acpi/property.c (ffffffff81585152)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:447
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff827231fc)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81643537)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff81688f6d)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff816c52d0)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff81726fa0)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff817320a6)
Location: include/acpi/acpi_bus.h:447
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d7ece)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db9e4)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd89d)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ef50)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff8186aa34)
Location: include/acpi/acpi_bus.h:447
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815230d0)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81541d1a)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff8158c33d)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff81594b5a)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff81599567)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8159c67b)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828db2d3)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff81661877)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff816a8c37)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff816e66be)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff81749780)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffffffff81754a96)
Location: include/acpi/acpi_bus.h:453
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff061)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802d90)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186aefe)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff8188ab04)
Location: include/acpi/acpi_bus.h:453
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff815515b7)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff815713c9)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815bd059)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff815c5bec)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ca859)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815ce079)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828f5bd4)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff816973a3)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff816e205e)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff8171fe58)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff817855f1)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8184029a)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8184418f)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aedf1)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In drivers/soundwire/slave.c (ffffffff818c26f0)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/soundwire/slave.c:sdw_acpi_find_slaves
```
```
In arch/x86/pci/acpi.c (ffffffff818d5315)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81572b77)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81592779)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815de319)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff815e6e1c)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ebad9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815ef2f9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828fec2b)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff816b9f6b)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff8170620e)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff81744128)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff817a9231)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81871bd3)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b05)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e12a1)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81907695)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81616f54)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff816411b4)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff81688d35)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff8169262c)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff81697549)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8169b509)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff82d15c1e)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (0)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81801ba1)
Location: include/acpi/acpi_bus.h:438
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8186eb31)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/usb/core/message.c (ffffffff818c3208)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81945ce3)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a43e)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b43a1)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81bb7dc5)
Location: include/acpi/acpi_bus.h:438
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d885)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81667657)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff816a6905)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff816b00dc)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff816b4699)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/acpi/property.c (ffffffff816b8369)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff830038c4)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (0)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81812961)
Location: include/acpi/acpi_bus.h:439
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8187d801)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/usb/core/message.c (ffffffff818cf512)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194bc26)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194ffce)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b69f1)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81bccb15)
Location: include/acpi/acpi_bus.h:439
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff816228fe)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81649ae5)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff81689595)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff816926bc)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff816968c9)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8169a309)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff816e4e46)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8320e44a)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (0)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff817f70ab)
Location: include/acpi/acpi_bus.h:440
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff8185ff73)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/usb/core/message.c (ffffffff818b2b3e)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8192f786)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933e80)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199b1a1)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81bc0545)
Location: include/acpi/acpi_bus.h:440
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8169207e)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff816bb99b)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/acpi/device_pm.c (ffffffff816fb9a9)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
```
In drivers/acpi/glue.c (ffffffff816fe9d5)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff8170820c)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff8170c669)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/acpi/property.c (ffffffff8170ff7d)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff8175dca6)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff832f71e5)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/mfd/mfd-core.c (ffffffff818803bb)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff818eed33)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff8190b743)
Location: include/acpi/acpi_bus.h:446
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81947e6e)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d2a26)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7280)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a47ae1)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81c90515)
Location: include/acpi/acpi_bus.h:446
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff817b166b)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_by_index
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff817dfd15)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/acpi/device_pm.c (ffffffff81828ee4)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
```
In drivers/acpi/glue.c (ffffffff8182c3ae)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff8183656d)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff8183ada5)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff8184011d)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff81891400)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff834af830)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81932471)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/mfd/mfd-core.c (ffffffff819c8a69)
Location: include/acpi/acpi_bus.h:450
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81a40f02)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81a5f003)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
```
In drivers/usb/core/message.c (ffffffff81aa08f7)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b351d1)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39fe7)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5a61)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff81e3f63d)
Location: include/acpi/acpi_bus.h:450
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff818cb0d7)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_by_index
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81902be5)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/acpi/device_pm.c (ffffffff8195b064)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
```
In drivers/acpi/glue.c (ffffffff8195ed96)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff8196a58d)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff81970453)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff819754d4)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff819d8bbd)
Location: include/acpi/acpi_bus.h:448
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:448
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81a90f4f)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/mfd/mfd-core.c (ffffffff81b3fdb5)
Location: include/acpi/acpi_bus.h:448
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81bc7132)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81bea373)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
```
In drivers/usb/core/message.c (ffffffff81c25e6b)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca35e)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf967)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a321)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff8201952d)
Location: include/acpi/acpi_bus.h:448
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8190c690)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81946275)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/acpi/device_pm.c (ffffffff819a1534)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
```
In drivers/acpi/glue.c (ffffffff819a535a)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff819b0b4d)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff819b6ad4)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff819bbd18)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff81a2068d)
Location: include/acpi/acpi_bus.h:451
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:451
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81adc75e)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/mfd/mfd-core.c (ffffffff81b93145)
Location: include/acpi/acpi_bus.h:451
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81c1ece2)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81c427a4)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
```
In drivers/usb/core/message.c (ffffffff81c8ce11)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32d08)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37a60)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4cc1)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff82099bad)
Location: include/acpi/acpi_bus.h:451
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81954280)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff8198f5a5)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/acpi/device_pm.c (ffffffff819e9be4)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_storage_d3
```
```
In drivers/acpi/glue.c (ffffffff819edcd9)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f30cd)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
```
```
In drivers/acpi/dock.c (ffffffff819fb06d)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff81a01084)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff81a065c8)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffffffff81a6b9dc)
Location: include/acpi/acpi_bus.h:546
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/acpi/acpi_bus.h:546
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81b2fa5e)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/mfd/mfd-core.c (ffffffff81be70e5)
Location: include/acpi/acpi_bus.h:546
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81c73e12)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
```
In drivers/net/mdio/acpi_mdio.c (ffffffff81cf7e64)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
```
In drivers/usb/core/message.c (ffffffff81d41932)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8d28)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedce0)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d601)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff821712dd)
Location: include/acpi/acpi_bus.h:546
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In arch/arm64/kernel/pci.c (ffff8000100a7c54)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/arm64/kernel/pci.c:pcibios_root_bridge_prepare
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f48c)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca950)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffff8000106f85cc)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffff80001076a704)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffff800010773fec)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffff800010776f94)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/acpi_amba.c (ffff800010777468)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffff800010779f60)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (ffff8000107a446c)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffff800011482794)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffff8000108a992c)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffff8000108f30d0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffff8000109401fc)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffff8000109b5e34)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (ffff8000109c3264)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab537c)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba954)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b640)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/base/property.c (0)
Location: include/linux/acpi.h:720
Inline: True
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
In drivers/base/property.c (0)
Location: include/linux/acpi.h:720
Inline: True
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
In drivers/base/property.c (0)
Location: include/linux/acpi.h:720
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81568337)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff81586609)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815d07f9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/acpi_platform.c (ffffffff815daeb9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815ddf89)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828e64a3)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff8167f9cb)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff816cb95e)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff817021c8)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8176e2f1)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884c61)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff818a6a55)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81559187)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff815753d9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815ba3b9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/acpi_platform.c (ffffffff815c64f9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815c95c9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828dec98)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/base/property.c (ffffffff816a6c8e)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5fd8)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8174e141)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In arch/x86/pci/acpi.c (ffffffff81861575)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81566ea7)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff815864c9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815d25f9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff815db0fc)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff815dfdb9)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815e35d9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828f9f4e)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff816addab)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff816f9ece)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff817375e8)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff8179e0b1)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81865d63)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868cad)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186afb5)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d6101)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff818f80b5)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81580dc7)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
```
In drivers/pci/pci-acpi.c (ffffffff815a0979)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/glue.c (ffffffff815ec4b9)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/dock.c (ffffffff815f4fbc)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/acpi/acpi_platform.c (ffffffff815f9c79)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/acpi/property.c (ffffffff815fd499)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/acpi/container.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff828ffc7f)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
```
```
In drivers/tty/serdev/core.c (ffffffff816c820b)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/base/property.c (ffffffff8171476e)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
```
```
In drivers/mfd/mfd-core.c (ffffffff81752a28)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/ata/libata-acpi.c (ffffffff817b7f31)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/spi/spi.c (0)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881013)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884f45)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2c21)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In arch/x86/pci/acpi.c (ffffffff819191b5)
Location: include/acpi/acpi_bus.h:437
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
</details>
</li>
</ul>

## Differences
