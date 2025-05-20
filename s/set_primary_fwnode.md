# Function: <code>set_primary_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547170)
Location: drivers/base/core.c:2256
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81547170-ffffffff815471fb: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598df0)
Location: drivers/base/core.c:2256
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/property.c:device_remove_properties
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81598df0-ffffffff81598e7b: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6630)
Location: drivers/base/core.c:2847
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/property.c:device_remove_properties
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff815c6630-ffffffff815c66bb: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db360)
Location: drivers/base/core.c:2849
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/property.c:device_remove_properties
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff815db360-ffffffff815db3c5: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642320)
Location: drivers/base/core.c:2985
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/property.c:device_remove_properties
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81642320-ffffffff81642389: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d5c0)
Location: drivers/base/core.c:3040
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/property.c:device_remove_properties
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff8167d5c0-ffffffff8167d629: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169cfb0)
Location: drivers/base/core.c:3115
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff8169cfb0-ffffffff8169d019: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816d5eb2)
Location: drivers/base/core.c:3369
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff816d899d-ffffffff816d89b8: set_primary_fwnode.cold (STB_LOCAL)
ffffffff816d5e60-ffffffff816d5ed9: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9eb0)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff816f9eb0-ffffffff816f9f11: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b1a00)
Location: drivers/base/core.c:3989
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff817b1a00-ffffffff817b1a74: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c62f0)
Location: drivers/base/core.c:4442
Inline: False
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff817c62f0-ffffffff817c6376: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817a9650)
Location: drivers/base/core.c:4669
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff817a9650-ffffffff817a96d6: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81832820)
Location: drivers/base/core.c:4734
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81832820-ffffffff818328a6: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81973fa0)
Location: drivers/base/core.c:4773
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81973fa0-ffffffff81974057: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81adf600)
Location: drivers/base/core.c:4992
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81adf600-ffffffff81adf6b7: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2d8a0)
Location: drivers/base/core.c:4997
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81b2d8a0-ffffffff81b2d957: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b850a0)
Location: drivers/base/core.c:5011
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff81b850a0-ffffffff81b85157: set_primary_fwnode (STB_GLOBAL)
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
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4480)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - arch/arm64/kernel/pci.c:pcibios_root_bridge_prepare
  - arch/arm64/kernel/pci.c:pcibios_root_bridge_prepare
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
**Symbols:**

```
ffff8000108e4480-ffff8000108e4508: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2ed4)
Location: drivers/base/core.c:3521
Inline: True
```
**Symbols:**

```
c09d2ed4-c09d2f6c: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000977890)
Location: drivers/base/core.c:3521
Inline: False
```
**Symbols:**

```
c000000000977890-c000000000977908: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005793d0)
Location: drivers/base/core.c:3521
Inline: True
```
**Symbols:**

```
ffffffe0005793d0-ffffffe00057943e: set_primary_fwnode (STB_GLOBAL)
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
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf6a0)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff816bf6a0-ffffffff816bf701: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a950)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff8169a950-ffffffff8169a9b1: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816edb70)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff816edb70-ffffffff816edbd1: set_primary_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_primary_fwnode(struct device *dev, struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817083b0)
Location: drivers/base/core.c:3521
Inline: True
Direct callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/base/platform.c:platform_device_register_full
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - arch/x86/pci/acpi.c:pcibios_root_bridge_prepare
```
**Symbols:**

```
ffffffff817083b0-ffffffff81708411: set_primary_fwnode (STB_GLOBAL)
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
