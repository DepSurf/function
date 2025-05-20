# Function: <code>driver_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8154c9a0)
Location: drivers/base/driver.c:188
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_driver_exit
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8154c9a0-ffffffff8154c9ea: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8159e790)
Location: drivers/base/driver.c:188
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8159e790-ffffffff8159e7da: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815ccd40)
Location: drivers/base/driver.c:188
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff815ccd40-ffffffff815ccd8a: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815e1890)
Location: drivers/base/driver.c:188
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff815e1890-ffffffff815e18cf: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816489f0)
Location: drivers/base/driver.c:188
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816489f0-ffffffff81648a30: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81683f70)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81683f70-ffffffff81683fb0: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a3c40)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816a3c40-ffffffff816a3c80: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816dcb40)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/soundwire/bus_type.c:sdw_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816dcb40-ffffffff816dcb84: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81700bf0)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81700bf0-ffffffff81700c37: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817baa50)
Location: drivers/base/driver.c:191
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff817baa50-ffffffff817baa9b: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817cf6a0)
Location: drivers/base/driver.c:191
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff817cf6a0-ffffffff817cf6eb: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817b30b0)
Location: drivers/base/driver.c:191
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff817b30b0-ffffffff817b30fb: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8183c5a0)
Location: drivers/base/driver.c:191
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8183c5a0-ffffffff8183c5eb: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8197efc0)
Location: drivers/base/driver.c:261
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8197efc0-ffffffff8197f019: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81aec6e0)
Location: drivers/base/driver.c:267
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81aec6e0-ffffffff81aec739: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b3a9b0)
Location: drivers/base/driver.c:267
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/serial_base_bus.c:serial_base_driver_unregister
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81b3a9b0-ffffffff81b3aa09: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b92470)
Location: drivers/base/driver.c:267
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/serial_base_bus.c:serial_base_driver_unregister
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/auxiliary.c:auxiliary_driver_unregister
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff81b92470-ffffffff81b924c9: driver_unregister (STB_GLOBAL)
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
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffff8000108ec098)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_driver_unregister
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/amba/bus.c:amba_driver_unregister
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/mfd/stmpe-spi.c:stmpe_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/firmware/arm_scmi/bus.c:scmi_driver_unregister
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffff8000108ec098-ffff8000108ec0f4: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c09da0c0)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/amba/bus.c:amba_driver_unregister
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/mfd/stmpe-spi.c:stmpe_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/firmware/arm_scmi/bus.c:scmi_driver_unregister
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
c09da0c0-c09da11c: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c000000000983a90)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_unregister_driver
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/mfd/stmpe-spi.c:stmpe_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
c000000000983a90-c000000000983b18: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffe00057f6a0)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/mfd/stmpe-spi.c:stmpe_exit
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/mmc/host/mmc_spi.c:mmc_spi_driver_exit
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffe00057f6a0-ffffffe00057f6f6: driver_unregister (STB_GLOBAL)
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
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816c63e0)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816c63e0-ffffffff816c6427: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a1640)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/nvdimm/pmem.c:nd_pmem_driver_exit
  - drivers/nvdimm/blk.c:nd_blk_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/dax/pmem/pmem.c:dax_pmem_exit
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/hv/vmbus_drv.c:vmbus_driver_unregister
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816a1640-ffffffff816a1687: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816f48b0)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816f48b0-ffffffff816f48f7: driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void driver_unregister(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8170f140)
Location: drivers/base/driver.c:190
Inline: True
Direct callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pcie/portdrv_core.c:pcie_port_service_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_unregister_driver
  - drivers/rapidio/rio-driver.c:rio_unregister_driver
  - drivers/acpi/bus.c:acpi_bus_unregister_driver
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/pnp/driver.c:pnp_unregister_driver
  - drivers/virtio/virtio.c:unregister_virtio_driver
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_unregister_driver
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/base/platform.c:platform_unregister_drivers
  - drivers/base/platform.c:__platform_register_drivers
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm.c:nvdimm_exit
  - drivers/nvdimm/region.c:nd_region_exit
  - drivers/dax/bus.c:dax_driver_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sr.c:exit_sr
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_driver_unregister
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_unregister
  - drivers/net/phy/phy_device.c:phy_drivers_register
  - drivers/net/phy/mdio_device.c:mdio_driver_unregister
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_register_driver
  - drivers/usb/core/driver.c:usb_deregister_device_driver
  - drivers/input/serio/serio.c:serio_unregister_driver
  - drivers/input/serio/serio.c:__serio_register_driver
  - drivers/eisa/eisa-bus.c:eisa_driver_unregister
  - drivers/mmc/core/bus.c:mmc_unregister_driver
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_driver
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8170f140-ffffffff8170f187: driver_unregister (STB_GLOBAL)
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
