# Function: <code>bus_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a650)
Location: drivers/base/bus.c:888
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
```
**Symbols:**

```
ffffffff8154a650-ffffffff8154a8cb: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c340)
Location: drivers/base/bus.c:887
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
```
**Symbols:**

```
ffffffff8159c340-ffffffff8159c5b5: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca8a0)
Location: drivers/base/bus.c:887
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
```
**Symbols:**

```
ffffffff815ca8a0-ffffffff815cab15: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df520)
Location: drivers/base/bus.c:846
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff815df520-ffffffff815df78f: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646550)
Location: drivers/base/bus.c:846
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_register
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81646550-ffffffff816467bf: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681a30)
Location: drivers/base/bus.c:844
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81681a30-ffffffff81681c9d: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a14d0)
Location: drivers/base/bus.c:851
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff816a14d0-ffffffff816a173e: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da2b0)
Location: drivers/base/bus.c:825
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/soundwire/bus_type.c:sdw_bus_init
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff816da2b0-ffffffff816da51d: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe260)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff816fe260-ffffffff816fe4cd: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7db0)
Location: drivers/base/bus.c:802
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff817b7db0-ffffffff817b8179: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817ccad0)
Location: drivers/base/bus.c:802
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff817ccad0-ffffffff817cce6a: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b0440)
Location: drivers/base/bus.c:785
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff817b0440-ffffffff817b07e4: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81839660)
Location: drivers/base/bus.c:781
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81839660-ffffffff81839a04: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197bc70)
Location: drivers/base/bus.c:783
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff8197bc70-ffffffff8197c033: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8d80)
Location: drivers/base/bus.c:783
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/staging/vme_user/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81ae8d80-ffffffff81ae9140: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bus_register(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b37080)
Location: drivers/base/bus.c:844
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/soc.c:soc_bus_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/staging/vme_user/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81b37080-ffffffff81b3739f: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bus_register(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8ead0)
Location: drivers/base/bus.c:844
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/auxiliary.c:auxiliary_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/soc.c:soc_bus_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/staging/vme_user/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff81b8ead0-ffffffff81b8ee1f: bus_register (STB_GLOBAL)
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
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8de8)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/amba/bus.c:amba_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/power/domain.c:genpd_bus_init
  - drivers/base/soc.c:soc_bus_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_init
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffff8000108e8de8-ffff8000108e902c: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d710c)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/amba/bus.c:amba_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/power/domain.c:genpd_bus_init
  - drivers/base/soc.c:soc_bus_register
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_init
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
  - sound/ac97_bus.c:ac97_bus_init
```
**Symbols:**

```
c09d710c-c09d7350: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097fad0)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_init
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/power/domain.c:genpd_bus_init
  - drivers/base/soc.c:soc_bus_register
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
c00000000097fad0-c00000000097fde4: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057d19e)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/power/domain.c:genpd_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffe00057d19e-ffffffe00057d3e4: bus_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3a50)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff816c3a50-ffffffff816c3cbd: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169ed00)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff8169ed00-ffffffff8169ef6d: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1f20)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff816f1f20-ffffffff816f218d: bus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_register(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c760)
Location: drivers/base/bus.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_sysfs_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/pci-driver.c:pci_driver_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/pnp/core.c:pnp_init
  - drivers/virtio/virtio.c:virtio_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend_init
  - drivers/tty/serdev/core.c:serdev_init
  - drivers/base/bus.c:subsys_virtual_register
  - drivers/base/bus.c:subsys_system_register
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_bus_init
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_init
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/eisa/eisa-bus.c:eisa_init
  - drivers/mmc/core/bus.c:mmc_register_bus
  - drivers/mmc/core/sdio_bus.c:sdio_register_bus
  - drivers/vme/vme.c:vme_init
  - drivers/nvmem/core.c:nvmem_init
```
**Symbols:**

```
ffffffff8170c760-ffffffff8170c9cd: bus_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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
