# Function: <code>device_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815483f0)
Location: drivers/base/core.c:1025
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815483f0-ffffffff81548a69: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a040)
Location: drivers/base/core.c:1025
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/pci/probe.c:pci_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/net/phy/mdio_device.c:mdio_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8159a040-ffffffff8159a692: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c85d0)
Location: drivers/base/core.c:1607
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/pci/probe.c:pci_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/net/phy/mdio_device.c:mdio_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815c85d0-ffffffff815c8bfb: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dd2a0)
Location: drivers/base/core.c:1605
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815dd2a0-ffffffff815dd918: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816442a0)
Location: drivers/base/core.c:1740
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816442a0-ffffffff8164491e: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167f6f0)
Location: drivers/base/core.c:1782
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8167f6f0-ffffffff8167fd34: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169e3e0)
Location: drivers/base/core.c:1858
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169e3e0-ffffffff8169ea72: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d6990)
Location: drivers/base/core.c:2062
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816d6990-ffffffff816d7032: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816faa90)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816faa90-ffffffff816fb132: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3cd0)
Location: drivers/base/core.c:2579
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:__cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_add_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817b3cd0-ffffffff817b436b: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ca3a0)
Location: drivers/base/core.c:2988
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:__cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_add_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817ca3a0-ffffffff817ca98c: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817adc80)
Location: drivers/base/core.c:3206
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_add_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817adc80-ffffffff817ae2fd: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3274
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:__spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/net/phy/mdio_device.c:mdio_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81d02c5a-ffffffff81d02c6e: device_add.cold (STB_LOCAL)
ffffffff81836d70-ffffffff81837512: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3309
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:__spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/net/phy/mdio_device.c:mdio_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81ecb3a0-ffffffff81ecb3b5: device_add.cold (STB_LOCAL)
ffffffff81978db0-ffffffff819795b6: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3507
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:__spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff82098348-ffffffff8209835d: device_add.cold (STB_LOCAL)
ffffffff81ae5950-ffffffff81ae6071: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3508
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:__spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff82119374-ffffffff82119389: device_add.cold (STB_LOCAL)
ffffffff81b33d20-ffffffff81b34420: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3521
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device_adapter
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_drv.c:drm_minor_register
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:__spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff821f7337-ffffffff821f734c: device_add.cold (STB_LOCAL)
ffffffff81b8b6b0-ffffffff81b8bdf0: device_add (STB_GLOBAL)
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
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e50d8)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_device_add
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffff8000108e50d8-ffff8000108e5718: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d387c)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - sound/core/sound.c:snd_register_device
  - sound/soc/soc-ac97.c:snd_soc_new_ac97_component
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c09d387c-c09d3ed0: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a940)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/of/device.c:of_device_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c00000000097a940-c00000000097b174: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579ebe)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffe000579ebe-ffffffe00057a430: device_add (STB_GLOBAL)
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
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0280)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816c0280-ffffffff816c0922: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169b530)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169b530-ffffffff8169bbd2: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ee750)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816ee750-ffffffff816eedf2: device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_add(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708c70)
Location: drivers/base/core.c:2099
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_add
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/attribute_container.c:attribute_container_add_class_device
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_async_device_register
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_register
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/input.c:input_register_device
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81708c70-ffffffff81709312: device_add (STB_GLOBAL)
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
