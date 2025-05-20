# Function: <code>get_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815468c0)
Location: drivers/base/core.c:1201
Inline: True
Inline callers:
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:bdget_disk
  - block/genhd.c:blk_lookup_devt
  - block/bsg.c:bsg_register_queue
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:_regulator_get
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/base/bus.c:bus_find_device
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_detach
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core.c:i2c_use_client
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/extcon/extcon.c:extcon_dev_unregister
```
**Symbols:**

```
ffffffff815468c0-ffffffff815468e0: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159af9f)
Location: drivers/base/core.c:1201
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - mm/backing-dev.c:bdi_register_owner
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg.c:bsg_register_queue
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/i2c/i2c-core.c:i2c_use_client
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/extcon/extcon.c:extcon_dev_unregister
```
**Symbols:**

```
ffffffff81598540-ffffffff81598560: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c94ff)
Location: drivers/base/core.c:1787
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - mm/backing-dev.c:bdi_register_owner
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg.c:bsg_register_queue
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/gpio/gpiolib.c:gpiod_request
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tlink_add
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/i2c/i2c-core.c:i2c_use_client
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/extcon/extcon.c:extcon_dev_unregister
```
**Symbols:**

```
ffffffff815c60d0-ffffffff815c60f0: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815de21f)
Location: drivers/base/core.c:1785
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg.c:bsg_register_queue
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff815daf40-ffffffff815daf60: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8164521f)
Location: drivers/base/core.c:1920
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg.c:bsg_register_queue
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81641f00-ffffffff81641f20: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81680669)
Location: drivers/base/core.c:1967
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg-lib.c:bsg_request_fn
  - block/bsg-lib.c:bsg_request_fn
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8167d190-ffffffff8167d1b0: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816a00f9)
Location: drivers/base/core.c:2046
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8169cb20-ffffffff8169cb40: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d8809)
Location: drivers/base/core.c:2250
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff816d58f0-ffffffff816d5908: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fc90e)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff816f96e0-ffffffff816f96f8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b62f4)
Location: drivers/base/core.c:2785
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
  - block/genhd.c:disk_part_iter_next
  - block/partitions/core.c:delete_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_init
```
**Symbols:**

```
ffffffff817b25d0-ffffffff817b25e8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817cb764)
Location: drivers/base/core.c:3194
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_init
```
**Symbols:**

```
ffffffff817c6fb0-ffffffff817c6fc8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817af0d4)
Location: drivers/base/core.c:3421
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_link_device
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff817aa480-ffffffff817aa498: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818382f6)
Location: drivers/base/core.c:3486
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/partitions/core.c:add_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_open
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81833660-ffffffff81833678: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8197a666)
Location: drivers/base/core.c:3521
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:__fw_devlink_link_to_suppliers
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/partitions/core.c:add_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_init
```
**Symbols:**

```
ffffffff81974db0-ffffffff81974dd4: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae74d6)
Location: drivers/base/core.c:3720
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/partitions/core.c:add_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_group_store_type
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_bus.c:sdio_alloc_func
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_init
```
**Symbols:**

```
ffffffff81ae0510-ffffffff81ae0534: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b358c0)
Location: drivers/base/core.c:3719
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/partitions/core.c:add_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_bus.c:sdio_alloc_func
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_init
```
**Symbols:**

```
ffffffff81b2e730-ffffffff81b2e754: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8d2e0)
Location: drivers/base/core.c:3733
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_any_child
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:__fw_devlink_relax_cycles
  - drivers/base/core.c:fw_devlink_dev_sync_state
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - mm/backing-dev.c:bdi_set_owner
  - mm/backing-dev.c:bdi_set_owner
  - block/partitions/core.c:add_partition
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/phy/phy-core.c:phy_get
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpio_device_find_by_fwnode
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/intel/dmar.c:dmar_acpi_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:bus_get_dev_root
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_async_fn
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
  - drivers/base/memory.c:find_memory_block
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_lib.c:scsi_device_from_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_get
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mii_timestamper.c:register_mii_timestamper
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_bus.c:sdio_alloc_func
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_dev_get
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/page_pool.c:page_pool_init
  - net/devlink/core.c:devlink_alloc_ns
```
**Symbols:**

```
ffffffff81b85f30-ffffffff81b85f54: get_device (STB_GLOBAL)
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
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e732c)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/amba/bus.c:amba_find_match
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/ethernet/freescale/fman/fman.c:fman_bind
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_bind
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
  - drivers/of/device.c:of_dev_get
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffff8000108e3a90-ffff8000108e3ac4: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d591c)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/amba/bus.c:amba_find_match
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
  - drivers/of/device.c:of_dev_get
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - sound/core/sound.c:snd_lookup_minor_data
  - sound/core/init.c:snd_card_file_add
  - sound/core/init.c:snd_card_ref
  - sound/core/sound_oss.c:snd_lookup_oss_minor_data
  - sound/core/timer.c:snd_timer_open
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
c09d2440-c09d246c: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097d5e4)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_remove
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/misc/cxl/base.c:cxl_afu_get
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_transport_srp.c:srp_rport_add
  - drivers/scsi/scsi_transport_srp.c:srp_rport_get
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/of/device.c:of_dev_get
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
c000000000978a70-c000000000978ab8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057bada)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/phy/phy-core.c:devm_of_phy_get_by_index
  - drivers/phy/phy-core.c:of_phy_get
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:scsi_disk_get
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
  - drivers/of/device.c:of_dev_get
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffe000578c3e-ffffffe000578c6c: get_device (STB_GLOBAL)
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
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c20fe)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_sysfs_delete
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff816beed0-ffffffff816beee8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d3ae)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_sysfs_delete
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/hv/channel_mgmt.c:vmbus_onoffer_rescind
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff8169a180-ffffffff8169a198: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f05ce)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff816ed3a0-ffffffff816ed3b8: get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct device *get_device(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8170ae0e)
Location: drivers/base/core.c:2287
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_rename
  - drivers/base/core.c:device_find_child_by_name
  - drivers/base/core.c:device_find_child
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:klist_children_get
  - drivers/base/core.c:device_links_unbind_consumers
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/posix-clock.c:posix_clock_open
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_get_part
  - block/bsg-lib.c:bsg_queue_rq
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/pci/bus.c:pci_bus_get
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pcie/portdrv_core.c:pcie_port_probe_service
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/rapidio/rio-driver.c:rio_device_probe
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show
  - drivers/acpi/bus.c:acpi_device_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:get_acpi_device
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/char/tpm/tpm-chip.c:tpm_try_get_ops
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/base/bus.c:klist_devices_get
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:subsys_find_device_by_id
  - drivers/base/bus.c:bus_find_device
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/driver.c:driver_find_device
  - drivers/base/class.c:klist_class_dev_get
  - drivers/base/attribute_container.c:attribute_container_add_device
  - drivers/base/attribute_container.c:internal_container_klist_get
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/claim.c:__nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/scsi/scsi.c:scsi_device_get
  - drivers/scsi/hosts.c:scsi_host_lookup
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sd.c:sd_probe
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy_10g
  - drivers/net/phy/phy_device.c:phy_driver_is_genphy
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/usb.c:usb_get_intf
  - drivers/usb/core/usb.c:usb_get_dev
  - drivers/usb/phy/phy.c:usb_get_phy
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_use_client
  - drivers/media/cec/cec-core.c:cec_get_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81707be0-ffffffff81707bf8: get_device (STB_GLOBAL)
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
