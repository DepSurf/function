# Function: <code>bus_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a500)
Location: drivers/base/bus.c:973
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/edac/edac_stub.c:edac_put_sysfs_subsys
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/vme/vme.c:vme_exit
```
**Symbols:**

```
ffffffff8154a500-ffffffff8154a5b6: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c140)
Location: drivers/base/bus.c:972
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/vme/vme.c:vme_exit
```
**Symbols:**

```
ffffffff8159c140-ffffffff8159c1ee: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca6a0)
Location: drivers/base/bus.c:972
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
```
**Symbols:**

```
ffffffff815ca6a0-ffffffff815ca74e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df370)
Location: drivers/base/bus.c:931
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_module.c:edac_exit
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff815df370-ffffffff815df41e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816463a0)
Location: drivers/base/bus.c:931
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/pcie/portdrv_bus.c:pcie_port_bus_unregister
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_module.c:edac_exit
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816463a0-ffffffff8164644e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681880)
Location: drivers/base/bus.c:929
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff81681880-ffffffff8168192e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a1320)
Location: drivers/base/bus.c:936
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816a1320-ffffffff816a13ce: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da0f0)
Location: drivers/base/bus.c:910
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/soundwire/bus_type.c:sdw_bus_exit
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816da0f0-ffffffff816da19e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe0a0)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816fe0a0-ffffffff816fe14e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7b70)
Location: drivers/base/bus.c:887
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff817b7b70-ffffffff817b7cde: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc890)
Location: drivers/base/bus.c:887
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff817cc890-ffffffff817cc9fe: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b0200)
Location: drivers/base/bus.c:870
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff817b0200-ffffffff817b036e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81839420)
Location: drivers/base/bus.c:866
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff81839420-ffffffff8183958e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197ba10)
Location: drivers/base/bus.c:868
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff8197ba10-ffffffff8197bb8a: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8b00)
Location: drivers/base/bus.c:868
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff81ae8b00-ffffffff81ae8c7a: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bus_unregister(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36e30)
Location: drivers/base/bus.c:929
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serial/serial_base_bus.c:serial_base_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff81b36e30-ffffffff81b36f5f: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bus_unregister(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e850)
Location: drivers/base/bus.c:929
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serial/serial_base_bus.c:serial_base_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff81b8e850-ffffffff81b8e97f: bus_unregister (STB_GLOBAL)
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
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e9030)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_driver_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffff8000108e9030-ffff8000108e90e0: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d7350)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
  - drivers/nvmem/core.c:nvmem_exit
  - sound/ac97_bus.c:ac97_bus_exit
```
**Symbols:**

```
c09d7350-c09d7408: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097f820)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/suspend.c:__machine_initcall_pseries_pseries_suspend_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
c00000000097f820-c00000000097f910: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057cfb2)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffe00057cfb2-ffffffe00057d070: bus_unregister (STB_GLOBAL)
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
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3890)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816c3890-ffffffff816c393e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169eb40)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff8169eb40-ffffffff8169ebee: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1d60)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff816f1d60-ffffffff816f1e0e: bus_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bus_unregister(struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c5a0)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_exit
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/isa.c:isa_bus_init
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_init
  - drivers/dax/bus.c:dax_bus_exit
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_register
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/serio.c:serio_exit
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/i2c/i2c-core-base.c:i2c_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/edac/edac_module.c:edac_exit
  - drivers/edac/edac_module.c:edac_init
  - drivers/mmc/core/bus.c:mmc_unregister_bus
  - drivers/mmc/core/sdio_bus.c:sdio_unregister_bus
  - drivers/nvmem/core.c:nvmem_exit
```
**Symbols:**

```
ffffffff8170c5a0-ffffffff8170c64e: bus_unregister (STB_GLOBAL)
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
