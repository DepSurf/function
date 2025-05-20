# Function: <code>device_unlock</code>

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
In drivers/pci/pci.c (ffffffff81434be7)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449e18)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
```
```
In drivers/base/core.c (ffffffff81546887)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/base/core.c:online_show
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff8154a1f4)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff8154b465)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/power/sysfs.c (ffffffff81553866)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81558f0d)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/nvdimm/core.c (ffffffff81596956)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_namespaces
  - drivers/nvdimm/core.c:flush_regions_dimms
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8159b4db)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
```
```
In drivers/nvdimm/claim.c (ffffffff815a0bd1)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815a1178)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1caf)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b1e59)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81607980)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/message.c (ffffffff81611eca)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_authorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81614f40)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81618376)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
```
```
In drivers/usb/core/devio.c (ffffffff81619c8a)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/core/devices.c (ffffffff8161e2a4)
Location: include/linux/device.h:965
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_read
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816204e7)
Location: include/linux/device.h:965
Inline: True
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
In drivers/pci/pci.c (ffffffff814805c9)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814960d8)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff8159af4e)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8159c098)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff8159df59)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
```
In drivers/base/power/sysfs.c (ffffffff815a5866)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815ad5cc)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff815ebb9b)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff815ec710)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3444)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/claim.c (ffffffff815f6f94)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815f751d)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f7db6)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160a294)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff8166a955)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81673760)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81674ef0)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8167888c)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff8167d11b)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8167f3f9)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8167f89c)
Location: include/linux/device.h:981
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680ed3)
Location: include/linux/device.h:981
Inline: True
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
In drivers/pci/pci.c (ffffffff814a1c19)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7a78)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff815c94ae)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff815ca5f8)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff815cc34f)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
```
In drivers/base/power/sysfs.c (ffffffff815d4026)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815dc38c)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8161878b)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816194f0)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81620d14)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/claim.c (ffffffff81625204)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8162578d)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626026)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff81639b74)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81698685)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff816a13f0)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff816a2b80)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816a656c)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff816aae9b)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff816ad139)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff816ad5dc)
Location: include/linux/device.h:1090
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816aec03)
Location: include/linux/device.h:1090
Inline: True
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
In drivers/pci/pci.c (ffffffff814acfda)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3d4e)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c22f8)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff815de1ce)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff815df2b8)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff815e0eb3)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
```
In drivers/base/platform.c (ffffffff815e30d6)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff815e8b8f)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815f0ee2)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8162c5cb)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8162d330)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff8163123a)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81635744)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8163a7ed)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b1e6)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164e6f4)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff816ad753)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff816b64ec)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff816b7d31)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816bb8c1)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff816bfe9b)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff816c22f8)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff816c27bc)
Location: include/linux/device.h:1094
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c38c3)
Location: include/linux/device.h:1094
Inline: True
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
In drivers/pci/pci.c (ffffffff814ec3aa)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f2d4b)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8150251b)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff816451ce)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816462e8)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff81647fc3)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
```
In drivers/base/platform.c (ffffffff8164a286)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff8164fe9f)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81658362)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8169524b)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81695ad3)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff81699a6a)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e0d4)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816a33ed)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a3e66)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b799a)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81718f69)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81721d7c)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81723601)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81727281)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff8172b8cb)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8172e0c8)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8172e58c)
Location: include/linux/device.h:1102
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172f6a3)
Location: include/linux/device.h:1102
Inline: True
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
In drivers/pci/pci.c (ffffffff8151bfbc)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81522fb0)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81530c08)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff81680618)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816817c7)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff816834aa)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff8168569b)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff8168b7b9)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81693d91)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816d137b)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816d1b83)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d5cee)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816da4eb)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816df57d)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816dfff6)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3cad)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81757c42)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81760bac)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817622b2)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817660e1)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff8176a9e7)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8176ced5)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8176d6d4)
Location: include/linux/device.h:1147
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176ec43)
Location: include/linux/device.h:1147
Inline: True
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
In drivers/pci/pci.c (ffffffff81533d4a)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538e10)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81548169)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81551211)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815578d8)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/core.c (ffffffff816a00a8)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816a1267)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff816a31aa)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816a530b)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816ab9e9)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816b4411)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816f2a1b)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816f3213)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f616a)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f776c)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc485)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8170192d)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817023b6)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff8171660d)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817526ee)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff8177c1b2)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff8178519c)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817868c2)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8178a651)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff8178ef77)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81791525)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81791d54)
Location: include/linux/device.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817932c3)
Location: include/linux/device.h:1200
Inline: True
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
In drivers/pci/pci.c (ffffffff8155f51b)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff815687f3)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff815781fc)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81581191)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158790a)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/core.c (ffffffff816d88cb)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816da007)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816dbf5e)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816de29e)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816e558c)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816ee2d8)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8172bf8f)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8172e1cb)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172fb72)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81730f20)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736548)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8173b7e1)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c298)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff81752137)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff8178e1f1)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff817b9afa)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817c332a)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817c4dad)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817c8ac7)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff817cd029)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817cfdd5)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817d0533)
Location: include/linux/device.h:1233
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1743)
Location: include/linux/device.h:1233
Inline: True
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
In drivers/pci/pci.c (ffffffff8158065b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81589a33)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8159997c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2c91)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a92ca)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815acdd2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816fc9d0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816fdfb7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816fff8e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff8170245e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff8170986c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817122b6)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff817501df)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8175246b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752bd2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff8175500c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a2d8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175f4ad)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8175ff48)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff817763b7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817b1e01)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817d1c00)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7cbe)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff817ea34a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817f3caa)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817f574d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817f9607)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff817fdcb1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81800c55)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81801403)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81802613)
Location: include/linux/device.h:1475
Inline: True
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
In drivers/pci/pci.c (ffffffff8162c0b9)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81630933)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8163915c)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b811)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651f55)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81655fd2)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
```
```
In drivers/base/core.c (ffffffff817b62a3)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff817b7b51)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817ba181)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff817bc19e)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff817c495c)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817cb7fc)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8180e8cf)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81810f16)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811612)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81813e2c)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81819df8)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181f2ed)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181fa48)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff818391c7)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81877b91)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff8189c817)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a5637)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff818b964f)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818c382a)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818c58fe)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818c9787)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff818ce3cc)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818d12ed)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818d1b53)
Location: include/linux/device.h:782
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d3143)
Location: include/linux/device.h:782
Inline: True
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
In drivers/pci/pci.c (ffffffff81651e09)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655fd3)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8165fc7c)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fb91)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674915)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81676572)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
```
```
In drivers/iommu/iommu.c (ffffffff817bbf8e)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff817cb713)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff817cc871)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817cefd1)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff817d0d26)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff817d93ec)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817e026c)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8181d43f)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8181fe56)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818204b2)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8182301c)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828f18)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8182e22d)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182e978)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff81834c3a)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81849a47)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff818864a1)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff818ab434)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b4777)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff818c7f2f)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818cfafa)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818d17ce)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818d48d7)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff818d931b)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818db75d)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818dbf33)
Location: include/linux/device.h:750
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dd593)
Location: include/linux/device.h:750
Inline: True
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
In drivers/pci/pci.c (ffffffff816348f9)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81638b2e)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8164216c)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652091)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656e45)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81658d12)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff8179f101)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff817af083)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff817b01de)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817b29e1)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff817b4746)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff817bd7bc)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817c4aac)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff818007cf)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81803142)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803792)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8180617c)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c138)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff818114fd)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811c48)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff81817e06)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182ce67)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81868d11)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897ad8)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff818ab59f)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818b312a)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818b4dee)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818b7ea7)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff818bc4a3)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818beb18)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818bf332)
Location: include/linux/device.h:756
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c0903)
Location: include/linux/device.h:756
Inline: True
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
In drivers/pci/pci.c (ffffffff816a49e9)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8e5e)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff816b2e3c)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3de1)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8dc5)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff816cacb2)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff81828104)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff818382a5)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81838d72)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8183be61)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff8183d886)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81847b3c)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff8184eebc)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8188abcf)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8188d69c)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e2d2)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8189046c)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896758)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8189b8ed)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c278)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff818a2430)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b8c37)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff818f8811)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff8194051f)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff8194857a)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8194a31b)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff8194d937)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff81952493)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81955178)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81955992)
Location: include/linux/device.h:773
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81957040)
Location: include/linux/device.h:773
Inline: True
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
In drivers/pci/pci.c (ffffffff817c6e51)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cbaee)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff817db7e0)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e9911)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ef019)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff817f1224)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff8196809b)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff8197a615)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff8197b2bc)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8197e3f6)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/driver.c (ffffffff8197ecc9)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff819805de)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff8198c713)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff819933f5)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff819d42de)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff819d6cd1)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d78e1)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da14c)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0e33)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e508d)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e5b06)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff819ebc19)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04527)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81a49ce1)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81a98774)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81aa0f18)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81aa2f87)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa67e1)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff81aabb35)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81aaeaa1)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81aaf62e)
Location: include/linux/device.h:848
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0cd0)
Location: include/linux/device.h:848
Inline: True
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
In drivers/pci/pci.c (ffffffff818e42f6)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff818eabf7)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff818fd738)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff8191967d)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff81ad165b)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff81ae7485)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81ae830c)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81aeb966)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/driver.c (ffffffff81aec3a1)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81aee0ee)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81afc2b3)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81b03a9c)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81b4eafe)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81b51873)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52711)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b5540c)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5c8f3)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b60ead)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b61a26)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff81b6880d)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83127)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81bd0151)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81c1b630)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81c26538)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c28a67)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2d5c1)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff81c33015)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81c36501)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81c3739f)
Location: include/linux/device.h:845
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38f80)
Location: include/linux/device.h:845
Inline: True
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
In drivers/pci/pci.c (ffffffff81924b0a)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192e1c7)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81940bc8)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff8195cc9d)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/base/core.c (ffffffff81b359b1)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81b35ea6)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81b39bd6)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:state_synced_store
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/driver.c (ffffffff81b3a591)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81b3c47e)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a6a3)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81b51afc)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81ba1f4e)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4d1d)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5bd1)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba895c)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bafec3)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb442d)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5026)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff81bbbc45)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd6e4f)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81c27dd1)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81c82555)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81c8d4f8)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_wireless_status_intf
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c8fa37)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81c94721)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff81c9a2f9)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81c9d7f1)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81c9e6df)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ca0330)
Location: include/linux/device.h:971
Inline: True
```
```
In drivers/platform/x86/intel/pmc/mtl.c (ffffffff81ddd0e8)
Location: include/linux/device.h:971
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
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
In drivers/pci/pci.c (ffffffff8196d1da)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976b47)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/aer.c (ffffffff81988c4b)
Location: include/linux/device.h:1003
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81989e28)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff819a62bd)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/base/core.c (ffffffff81b8d3d1)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
  - drivers/base/core.c:waiting_for_supplier_show
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81b8d8c6)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81b91696)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:state_synced_show
  - drivers/base/dd.c:state_synced_store
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/driver.c (ffffffff81b92051)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81b93fce)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81ba2a93)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81baa0ec)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81bf60de)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8f9a)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9e51)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfcafc)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c042f3)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c0897d)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c095a6)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/dax/bus.c (ffffffff81c103ce)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2bae6)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81cda3dc)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81d36e95)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81d42028)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_wireless_status_intf
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81d445e7)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81d491e1)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff81d4eec9)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81d523a1)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81d532df)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d54f80)
Location: include/linux/device.h:1003
Inline: True
```
```
In net/devlink/core.c (ffffffff82101237)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
```
```
In net/devlink/netlink.c (ffffffff82101c26)
Location: include/linux/device.h:1003
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_post_doit_dev_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
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
In drivers/pci/pci.c (ffff8000106e3144)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee3a0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffff800010701178)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b534)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712598)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffff800010716bc4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/amba/bus.c (ffff8000107b8b1c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/amba/bus.c:driver_override_store
  - drivers/amba/bus.c:driver_override_show
```
```
In drivers/base/core.c (ffff8000108e73dc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffff8000108e8cbc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffff8000108eb294)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffff8000108edafc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffff8000108f778c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffff800010902cc4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffff80001095022c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffff800010952ac4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffff8000109532f8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffff8000109560a8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095bba4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffff800010960c50)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/scsi/scsi_scan.c (ffff80001097a99c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffff8000109c2210)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffff800010a19bf4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffff800010a24994)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffff800010a26640)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffff800010a2a874)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffff800010a31574)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffff800010a34c78)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffff800010a35768)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a36de4)
Location: include/linux/device.h:1475
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087f00c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (c0889430)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (c0898e70)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (c08a1400)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/amba/bus.c (c08e4f9c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/amba/bus.c:driver_override_store
  - drivers/amba/bus.c:driver_override_show
```
```
In drivers/base/core.c (c09d58d4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (c09d7024)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (c09d93c8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (c09dbaa8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (c09e3644)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (c09ed114)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/scsi/scsi_scan.c (c0a4e3c4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (c0aaf0e8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (c0af1e14)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (c0afae34)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (c0afc770)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (c0b00404)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (c0b05264)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b0845c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (c0b08ee4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (c0b0a214)
Location: include/linux/device.h:1475
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/eeh_driver.c (c00000000004ab8c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
```
```
In drivers/pci/pci.c (c00000000085cf84)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (c00000000086aab4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/iov.c (c000000000886ea8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (c00000000097d590)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (c00000000097f670)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (c00000000098283c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (c0000000009860a0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (c000000000993114)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (c0000000009a126c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (c0000000009fc744)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (c0000000009ffc28)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00770)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (c000000000a03d50)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0ca5c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (c000000000a13fe4)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15054)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (c000000000a35488)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (c000000000a859ec)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (c000000000ab15c8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab7420)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (c000000000ad310c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (c000000000adf7f8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (c000000000ae1d10)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (c000000000ae7250)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (c000000000aee7fc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c000000000af25dc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (c000000000af383c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (c000000000af5970)
Location: include/linux/device.h:1475
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004baa08)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2c3e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffe0004cfed8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d8168)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/iov.c (ffffffe0004dff82)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffe00057bb8c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffe00057cea0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffe00057ef34)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffe000580d7e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffe0005882a8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/nvdimm/core.c (ffffffe0005c0506)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffe0005c2632)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2cc6)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c54dc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca11a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffe0005ce606)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e1b12)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffe000615da0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffe00063e690)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffe000646dae)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffe000648516)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffe00064c0c2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffe00064fe48)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffe000652580)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffe000652fc0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000653fa2)
Location: include/linux/device.h:1475
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
In drivers/pci/pci.c (ffffffff81574b7b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d8c3)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8158d80c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815964a1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ca9a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815a05a2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816c21c0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816c37a7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816c577e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816c7bae)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816cefbc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816d8636)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff817048cf)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81706b5b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817072c2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817096fc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e9c8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81713b9d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714638)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172aaa7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817768e1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff817a272a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817ac08a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817adb2d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817b19e7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff817b6091)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817b9035)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817b97e3)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ba9f3)
Location: include/linux/device.h:1475
Inline: True
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
In drivers/pci/pci.c (ffffffff815632db)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c693)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8157c34c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81585631)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bc2a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff8158f732)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/acpi/nfit/core.c (ffffffff815f948b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_shutdown
  - drivers/acpi/nfit/core.c:acpi_nfit_flush_probe
  - drivers/acpi/nfit/core.c:acpi_nvdimm_notify
  - drivers/acpi/nfit/core.c:scrub_show
  - drivers/acpi/nfit/core.c:scrub_show
  - drivers/acpi/nfit/core.c:hw_error_scrub_store
```
```
In drivers/base/core.c (ffffffff8169d470)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8169ea57)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816a09fe)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816a2eae)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816aa2ec)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816b2c96)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816d834f)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816da5db)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dad42)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd17c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2448)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816e761d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e80b8)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff81703ec7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81756691)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff8177bcb0)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781d6e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff8179456a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff8179da8a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8179f52d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817a3417)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff817a7ab1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817aaa65)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817ab213)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac413)
Location: include/linux/device.h:1475
Inline: True
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184daf3)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:driver_override_show
  - drivers/hv/vmbus_drv.c:driver_override_store
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
In drivers/pci/pci.c (ffffffff815743ab)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d783)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8158d6cc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815969e1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d01a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815a0b22)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816f0690)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816f1c77)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816f3c4e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816f611e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816fd52c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81705f76)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8174369f)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8174592b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746092)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817484cc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174d798)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175296d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753408)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff81769877)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817a6c81)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817c6a80)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817ccb3e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff817df1ca)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817e8b2a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817ea5cd)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817ee487)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff817f2b31)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817f5ad5)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817f6283)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f7493)
Location: include/linux/device.h:1475
Inline: True
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
In drivers/pci/pci.c (ffffffff8158e88b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_unlock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_bus_unlock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597c33)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff815a7b7c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0e61)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b744a)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815baf52)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff8170aece)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8170c4b7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8170e47e)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_driver_unlock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff817109ae)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff81717dbc)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81720941)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8175eaef)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81760d6b)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817614d2)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff8176394c)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81768c18)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8176dddd)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176e878)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff81784fe7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817c0b01)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817e0d20)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6dde)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/hub.c (ffffffff817f94ba)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81802d78)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8180480d)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff818086c7)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:remove_store
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
```
```
In drivers/usb/core/devio.c (ffffffff8180cdb1)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8180fd15)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818104c3)
Location: include/linux/device.h:1475
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818116d3)
Location: include/linux/device.h:1475
Inline: True
```
</details>
</li>
</ul>

## Differences
