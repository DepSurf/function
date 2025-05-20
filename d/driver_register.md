# Function: <code>driver_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8154c8c0)
Location: drivers/base/driver.c:148
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8154c8c0-ffffffff8154c994: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8159e6b0)
Location: drivers/base/driver.c:148
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_register_driver
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8159e6b0-ffffffff8159e784: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815ccc60)
Location: drivers/base/driver.c:148
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_register_driver
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff815ccc60-ffffffff815ccd34: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815e1790)
Location: drivers/base/driver.c:148
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff815e1790-ffffffff815e1864: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816488f0)
Location: drivers/base/driver.c:148
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816488f0-ffffffff816489c4: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81683fe4-ffffffff81684036: driver_register.cold.2 (STB_LOCAL)
ffffffff81683e90-ffffffff81683f46: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816a3cb4-ffffffff816a3d06: driver_register.cold.2 (STB_LOCAL)
ffffffff816a3b60-ffffffff816a3c16: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816dcbc4-ffffffff816dcc19: driver_register.cold (STB_LOCAL)
ffffffff816dca60-ffffffff816dcb20: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81700c77-ffffffff81700ccc: driver_register.cold (STB_LOCAL)
ffffffff81700b00-ffffffff81700bc6: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:147
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff817babe7-ffffffff817bac3d: driver_register.cold (STB_LOCAL)
ffffffff817baac0-ffffffff817baba3: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:147
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81c0e48d-ffffffff81c0e4df: driver_register.cold (STB_LOCAL)
ffffffff817cf710-ffffffff817cf7f7: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:147
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81c0088d-ffffffff81c008df: driver_register.cold (STB_LOCAL)
ffffffff817b3120-ffffffff817b3207: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:147
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81d031cf-ffffffff81d03221: driver_register.cold (STB_LOCAL)
ffffffff8183c610-ffffffff8183c6f7: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:216
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81ecb923-ffffffff81ecb976: driver_register.cold (STB_LOCAL)
ffffffff8197f060-ffffffff8197f15e: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81aec7a0)
Location: drivers/base/driver.c:222
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81aec7a0-ffffffff81aec8e6: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b3a870)
Location: drivers/base/driver.c:222
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serial/serial_base_bus.c:serial_base_driver_register
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81b3a870-ffffffff81b3a996: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b92330)
Location: drivers/base/driver.c:222
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serial/serial_base_bus.c:serial_base_driver_register
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:__auxiliary_driver_register
  - drivers/nvdimm/bus.c:__nd_driver_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81b92330-ffffffff81b92456: driver_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffff8000108ebf48)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:__fsl_mc_driver_register
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/amba/bus.c:amba_driver_register
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffff8000108ebf48-ffff8000108ec058: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c09d9f7c)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/amba/bus.c:amba_driver_register
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
c09d9f7c-c09da094: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c0000000009838a0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:__vio_register_driver
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/virtio/virtio.c:register_virtio_driver
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
c0000000009838a0-c000000000983a34: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffe00057f584)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffe00057f584-ffffffe00057f66a: driver_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816c6467-ffffffff816c64bc: driver_register.cold (STB_LOCAL)
ffffffff816c62f0-ffffffff816c63b6: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/hv/vmbus_drv.c:__vmbus_driver_register
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816a16c7-ffffffff816a171c: driver_register.cold (STB_LOCAL)
ffffffff816a1550-ffffffff816a1616: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816f4937-ffffffff816f498c: driver_register.cold (STB_LOCAL)
ffffffff816f47c0-ffffffff816f4886: driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int driver_register(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/driver.c (0)
Location: drivers/base/driver.c:146
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:__pci_register_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_register
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
  - drivers/rapidio/rio-driver.c:rio_register_driver
  - drivers/acpi/bus.c:acpi_bus_register_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_register_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_register_driver_common
  - drivers/tty/serdev/core.c:__serdev_device_driver_register
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:__dax_driver_register
  - drivers/scsi/scsi_sysfs.c:scsi_register_driver
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_register_full
  - drivers/spi/spi.c:__spi_register_driver
  - drivers/net/phy/phy_device.c:phy_driver_register
  - drivers/net/phy/mdio_device.c:mdio_driver_register
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_register
  - drivers/mmc/core/bus.c:mmc_register_driver
  - drivers/mmc/core/sdio_bus.c:sdio_register_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8170f1c7-ffffffff8170f21c: driver_register.cold (STB_LOCAL)
ffffffff8170f050-ffffffff8170f116: driver_register (STB_GLOBAL)
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
