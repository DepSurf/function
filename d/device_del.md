# Function: <code>device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81546dd0)
Location: drivers/base/core.c:1232
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - block/genhd.c:add_disk
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
  - block/partition-generic.c:add_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/base/core.c:device_unregister
  - drivers/base/platform.c:platform_device_del
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81546dd0-ffffffff8154702b: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598a50)
Location: drivers/base/core.c:1232
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/base/core.c:device_unregister
  - drivers/base/platform.c:platform_device_del
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81598a50-ffffffff81598cab: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7430)
Location: drivers/base/core.c:1818
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/base/core.c:device_unregister
  - drivers/base/platform.c:platform_device_del
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815c7430-ffffffff815c776e: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc110)
Location: drivers/base/core.c:1816
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_unregister
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff815dc110-ffffffff815dc456: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643140)
Location: drivers/base/core.c:1951
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_unregister
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81643140-ffffffff81643494: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167e250)
Location: drivers/base/core.c:1998
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_unregister
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8167e250-ffffffff8167e598: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169dc60)
Location: drivers/base/core.c:2077
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169dc60-ffffffff8169dfa1: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2299
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816d89de-ffffffff816d8a04: device_del.cold (STB_LOCAL)
ffffffff816d6020-ffffffff816d638a: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa060)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816fa060-ffffffff816fa3cc: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b31c0)
Location: drivers/base/core.c:2834
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817b31c0-ffffffff817b3487: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7a80)
Location: drivers/base/core.c:3243
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817c7a80-ffffffff817c7e59: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aaf90)
Location: drivers/base/core.c:3470
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff817aaf90-ffffffff817ab368: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818342e0)
Location: drivers/base/core.c:3535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff818342e0-ffffffff818346cf: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975db0)
Location: drivers/base/core.c:3570
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81975db0-ffffffff819761a0: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1e60)
Location: drivers/base/core.c:3769
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:delete_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81ae1e60-ffffffff81ae2250: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2fd90)
Location: drivers/base/core.c:3768
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_device_remove
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81b2fd90-ffffffff81b30163: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87590)
Location: drivers/base/core.c:3782
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_device_remove
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/gpu/drm/drm_drv.c:drm_minor_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/remoteproc/remoteproc_core.c:rproc_add
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81b87590-ffffffff81b87963: device_del (STB_GLOBAL)
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
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4868)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_remove
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffff8000108e4868-ffff8000108e4bb8: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d327c)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - sound/core/sound.c:snd_unregister_device
  - sound/core/init.c:snd_card_disconnect
  - sound/soc/soc-ac97.c:snd_soc_free_ac97_component
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c09d327c-c09d3604: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979c80)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_transport_srp.c:srp_rport_del
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
c000000000979c80-c00000000097a0e4: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579700)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffe000579700-ffffffe0005799e4: device_del (STB_GLOBAL)
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
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf850)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/nvme/host/core.c:nvme_destroy_subsystem
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816bf850-ffffffff816bfbbc: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ab00)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_transport_fc.c:fc_vport_terminate
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/scsi/sd.c:sd_remove
  - drivers/nvme/host/core.c:nvme_destroy_subsystem
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff8169ab00-ffffffff8169ae6c: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816edd20)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff816edd20-ffffffff816ee08c: device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_del(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708560)
Location: drivers/base/core.c:2336
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:pmu_dev_alloc
  - fs/char_dev.c:cdev_device_del
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:delete_partition
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/core.c:device_unregister
  - drivers/base/attribute_container.c:attribute_container_class_device_del
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/devcoredump.c:devcd_del
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/sd.c:sd_remove
  - drivers/ata/libata-transport.c:ata_tdev_delete
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_delete
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libata-transport.c:ata_tport_delete
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/phy/phy_device.c:phy_device_remove
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_remove
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:__input_unregister_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/mmc/core/bus.c:mmc_remove_card
  - drivers/mmc/core/host.c:mmc_remove_host
  - drivers/mmc/core/sdio_bus.c:sdio_remove_func
  - drivers/remoteproc/remoteproc_core.c:rproc_del
  - drivers/nvmem/core.c:nvmem_device_release
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/rfkill/core.c:rfkill_register
```
**Symbols:**

```
ffffffff81708560-ffffffff817088cc: device_del (STB_GLOBAL)
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
