# Function: <code>dev_set_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815467c0)
Location: drivers/base/core.c:931
Inline: False
Direct callers:
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/core.c:__nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815467c0-ffffffff8154682e: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598440)
Location: drivers/base/core.c:931
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81598440-ffffffff815984ae: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c5fd0)
Location: drivers/base/core.c:1513
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815c5fd0-ffffffff815c603e: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dae40)
Location: drivers/base/core.c:1511
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815dae40-ffffffff815daeae: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81641e00)
Location: drivers/base/core.c:1646
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - mm/hmm.c:hmm_device_new
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81641e00-ffffffff81641e6e: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d090)
Location: drivers/base/core.c:1688
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - mm/hmm.c:hmm_device_new
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8167d090-ffffffff8167d0fe: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ca20)
Location: drivers/base/core.c:1764
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - mm/hmm.c:hmm_device_new
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169ca20-ffffffff8169ca8e: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d57d0)
Location: drivers/base/core.c:1963
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/soundwire/slave.c:sdw_acpi_find_slaves
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816d57d0-ffffffff816d583a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f95c0)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816f95c0-ffffffff816f962a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b24b0)
Location: drivers/base/core.c:2480
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817b24b0-ffffffff817b251a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6f00)
Location: drivers/base/core.c:2889
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tdev_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817c6f00-ffffffff817c6f6a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa3d0)
Location: drivers/base/core.c:3107
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817aa3d0-ffffffff817aa43a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818335b0)
Location: drivers/base/core.c:3175
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff818335b0-ffffffff8183361a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81974ce0)
Location: drivers/base/core.c:3210
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/sysfs.c:fw_create_instance
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81974ce0-ffffffff81974d64: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0420)
Location: drivers/base/core.c:3408
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/sysfs.c:fw_create_instance
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81ae0420-ffffffff81ae04a4: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2e640)
Location: drivers/base/core.c:3423
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serial/serial_base_bus.c:serial_base_device_init
  - drivers/tty/serial/serial_base_bus.c:serial_base_device_init
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/sysfs.c:fw_create_instance
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81b2e640-ffffffff81b2e6c4: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b85e40)
Location: drivers/base/core.c:3436
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/pmdomain/core.c:pm_genpd_init
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serial/serial_base_bus.c:serial_base_device_init
  - drivers/tty/serial/serial_base_bus.c:serial_base_device_init
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_link_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/auxiliary.c:__auxiliary_device_add
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
  - drivers/base/firmware_loader/sysfs.c:fw_create_instance
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_minor_alloc
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/spi/spi.c:spi_dev_set_name
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81b85e40-ffffffff81b85ec4: dev_set_name (STB_GLOBAL)
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
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3828)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_device_add
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/amba/bus.c:amba_device_initialize
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
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
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffff8000108e3828-ffff8000108e38c0: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d222c)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/omap_device.c:omap_device_build
  - arch/arm/mach-omap2/hsmmc.c:omap_hsmmc_init
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/amba/bus.c:amba_device_initialize
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - sound/core/control.c:snd_ctl_create
  - sound/core/timer.c:alsa_timer_init
  - sound/core/pcm.c:snd_pcm_new_stream
  - sound/core/compress_offload.c:snd_compress_new
  - sound/soc/soc-core.c:snd_soc_instantiate_card
  - sound/soc/soc-ac97.c:snd_soc_alloc_ac97_component
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c09d222c-c09d2290: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000978940)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
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
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c000000000978940-c000000000978990: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000578b4c)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/platform.c:of_device_alloc
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffe000578b4c-ffffffe000578b94: dev_set_name (STB_GLOBAL)
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
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bedb0)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816bedb0-ffffffff816bee1a: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a060)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/hv/vmbus_drv.c:vmbus_device_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/vme/vme.c:vme_register_driver
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169a060-ffffffff8169a0ca: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed280)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816ed280-ffffffff816ed2ea: dev_set_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_set_name(struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707ac0)
Location: drivers/base/core.c:2000
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/pnp/core.c:pnp_alloc_dev
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card_device
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/tty/serdev/core.c:serdev_device_add
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_add
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/spi/spi.c:spi_add_device
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_create
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81707ac0-ffffffff81707b2a: dev_set_name (STB_GLOBAL)
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
