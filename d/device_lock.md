# Function: <code>device_lock</code>

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
In drivers/pci/pci.c (ffffffff81434b91)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81449ddb)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
```
```
In drivers/base/core.c (ffffffff8154686b)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/base/core.c:online_show
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff8154a1d3)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff8154b3db)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/power/sysfs.c (ffffffff8155384f)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81558eac)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/nvdimm/core.c (ffffffff8159694a)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_namespaces
  - drivers/nvdimm/core.c:flush_regions_dimms
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8159b49d)
Location: include/linux/device.h:955
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
In drivers/nvdimm/claim.c (ffffffff815a0baf)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_detach_ndns
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815a1149)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1c83)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b1e0b)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff816077b6)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/message.c (ffffffff8161372b)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_authorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81614f1e)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8161834d)
Location: include/linux/device.h:955
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
In drivers/usb/core/devio.c (ffffffff81619c65)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/core/devices.c (ffffffff8161e263)
Location: include/linux/device.h:955
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_read
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8162054c)
Location: include/linux/device.h:955
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
In drivers/pci/pci.c (ffffffff8148076c)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8149609b)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff8159afec)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8159c07f)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff8159df3b)
Location: include/linux/device.h:966
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
In drivers/base/power/sysfs.c (ffffffff815a584f)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815ad575)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff815ebb8b)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff815ec6dd)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3438)
Location: include/linux/device.h:966
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
In drivers/nvdimm/claim.c (ffffffff815f6f71)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815f74ee)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f7d53)
Location: include/linux/device.h:966
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
In drivers/scsi/scsi_scan.c (ffffffff8160a21d)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff8166a933)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff816736fb)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81674ece)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816788cd)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff8167d079)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8167f3b7)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8167f867)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680f3c)
Location: include/linux/device.h:966
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
In drivers/pci/pci.c (ffffffff814a1dbc)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7a3b)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff815c954c)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff815ca5df)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff815cc2e0)
Location: include/linux/device.h:1075
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
In drivers/base/power/sysfs.c (ffffffff815d400f)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815dc335)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8161877b)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816194bd)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81620d08)
Location: include/linux/device.h:1075
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
In drivers/nvdimm/claim.c (ffffffff816251e1)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/claim.c:nd_detach_ndns
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8162575e)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81625fc3)
Location: include/linux/device.h:1075
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
In drivers/scsi/scsi_scan.c (ffffffff81639afd)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81698663)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff816a138b)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff816a2b5e)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816a65ad)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff816aadf9)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff816ad0f7)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff816ad5a7)
Location: include/linux/device.h:1075
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816aec6c)
Location: include/linux/device.h:1075
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
In drivers/pci/pci.c (ffffffff814ab9c7)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:__pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3d09)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c22bb)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff815de26c)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff815df29f)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff815e0e90)
Location: include/linux/device.h:1079
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
In drivers/base/platform.c (ffffffff815e30ad)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff815e8b78)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff815f0eb1)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8162c5bb)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8162d2fd)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff8163120c)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81635738)
Location: include/linux/device.h:1079
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
In drivers/nvdimm/btt_devs.c (ffffffff8163a7be)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b183)
Location: include/linux/device.h:1079
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
In drivers/scsi/scsi_scan.c (ffffffff8164e67d)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff816ad71a)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff816b648b)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff816b7d0f)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816bb8fd)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff816bfdf6)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff816c22c7)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff816c2788)
Location: include/linux/device.h:1079
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c392d)
Location: include/linux/device.h:1079
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
In drivers/pci/pci.c (ffffffff814ebb38)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f2d1d)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff815024db)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:report_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:report_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:report_mmio_enabled
  - drivers/pci/pcie/aer/aerdrv_core.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff8164526c)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816462cf)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff81647fa0)
Location: include/linux/device.h:1087
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
In drivers/base/platform.c (ffffffff8164a25d)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff8164fe88)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff8165832f)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8169523b)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81695a9d)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff81699a3c)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e0c8)
Location: include/linux/device.h:1087
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
In drivers/nvdimm/btt_devs.c (ffffffff816a33be)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a3e03)
Location: include/linux/device.h:1087
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
In drivers/scsi/scsi_scan.c (ffffffff816b791d)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81718f4b)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81721d1b)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817235df)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817272bd)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff8172b826)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8172e097)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8172e558)
Location: include/linux/device.h:1087
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172f70d)
Location: include/linux/device.h:1087
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
In drivers/pci/pci.c (ffffffff8151a0a2)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81522f75)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81530bb5)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/base/core.c (ffffffff816806b6)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816817ac)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff81683490)
Location: include/linux/device.h:1132
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
In drivers/base/platform.c (ffffffff81685665)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff8168b7a1)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81693d41)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816d1365)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816d1b45)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d5cc0)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816da4db)
Location: include/linux/device.h:1132
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
In drivers/nvdimm/btt_devs.c (ffffffff816df54e)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816dffa5)
Location: include/linux/device.h:1132
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
In drivers/scsi/scsi_scan.c (ffffffff816f3c32)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/usb/core/hub.c (ffffffff81757afe)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81760b48)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8176228d)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81766115)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff8176a91c)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8176ce9d)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8176d6a0)
Location: include/linux/device.h:1132
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176ecac)
Location: include/linux/device.h:1132
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
In drivers/pci/pci.c (ffffffff8152fe32)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538dd5)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81548135)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815511e0)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815578bb)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/core.c (ffffffff816a0146)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816a124c)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_rescan_devices_helper
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
```
```
In drivers/base/dd.c (ffffffff816a3190)
Location: include/linux/device.h:1185
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
In drivers/base/platform.c (ffffffff816a52d5)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816ab9d1)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816b43c1)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816f2a05)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816f31d5)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f60d5)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f7742)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc479)
Location: include/linux/device.h:1185
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
In drivers/nvdimm/btt_devs.c (ffffffff817018fe)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81702365)
Location: include/linux/device.h:1185
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
In drivers/scsi/scsi_scan.c (ffffffff81716592)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817526a5)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff8177c06e)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81785138)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8178689d)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8178a685)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff8178eeac)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817914ed)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81791d20)
Location: include/linux/device.h:1185
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8179332c)
Location: include/linux/device.h:1185
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
In drivers/pci/pci.c (ffffffff8155f630)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff815687b5)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:sriov_numvfs_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff815781c5)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81581160)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815878ea)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/core.c (ffffffff816d8852)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816da011)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816dbf44)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816de265)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816e5571)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816ee28a)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8172bf75)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8172e139)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172fb25)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81730ef6)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736539)
Location: include/linux/device.h:1218
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
In drivers/nvdimm/btt_devs.c (ffffffff8173b7b2)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c248)
Location: include/linux/device.h:1218
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
In drivers/scsi/scsi_scan.c (ffffffff817520c2)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff8178e1a5)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff817b99ae)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817c32c8)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817c4d80)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817c8b05)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff817ccf4c)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817cfd9d)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817d04ff)
Location: include/linux/device.h:1218
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d17ad)
Location: include/linux/device.h:1218
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
In drivers/pci/pci.c (ffffffff81580770)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff815899f5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81599945)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2c60)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a92aa)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815acd64)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816fc957)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816fdfc1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816fff74)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff81702425)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff81709851)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81712268)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff817501c5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff817523d9)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752b85)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81754fe2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a2c9)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffff8175f47e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8175fef8)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (ffffffff81776342)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817b1db5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817d1c56)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff817ea1fe)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817f3c48)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817f5720)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817f9645)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff817fdbe2)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81800c1d)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818013cf)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8180267d)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffff8162c05d)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff816308f5)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81639125)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b7e0)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651f35)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81655f64)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
```
```
In drivers/base/core.c (ffffffff817b633d)
Location: include/linux/device.h:767
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
In drivers/base/bus.c (ffffffff817b7b5b)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817ba20a)
Location: include/linux/device.h:767
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
In drivers/base/platform.c (ffffffff817bc165)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff817c4941)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817cb7a8)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8180e8b5)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81810d76)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818115c5)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81813e02)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81819de9)
Location: include/linux/device.h:767
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
In drivers/nvdimm/btt_devs.c (ffffffff8181f2be)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181f9f8)
Location: include/linux/device.h:767
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
In drivers/scsi/scsi_scan.c (ffffffff81839152)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81877b45)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff8189c86d)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff818b959e)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818c37c8)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818c58d9)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818c97c5)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff818ce26c)
Location: include/linux/device.h:767
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818d12b5)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818d1b1f)
Location: include/linux/device.h:767
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d31ad)
Location: include/linux/device.h:767
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
In drivers/pci/pci.c (ffffffff81651dad)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655fab)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8165fc45)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fb60)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816748f5)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81676504)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
```
```
In drivers/iommu/iommu.c (ffffffff817bbf60)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff817cb7ad)
Location: include/linux/device.h:735
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
In drivers/base/bus.c (ffffffff817cc87b)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817cf05a)
Location: include/linux/device.h:735
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
In drivers/base/platform.c (ffffffff817d0d02)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff817d93d1)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817e0218)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8181d425)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8181fcb6)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820481)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822ff2)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828f09)
Location: include/linux/device.h:735
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
In drivers/nvdimm/btt_devs.c (ffffffff8182e1fe)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182e928)
Location: include/linux/device.h:735
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
In drivers/dax/bus.c (ffffffff81834c05)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff818499d2)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81886455)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff818ab48a)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff818c7e7e)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818cfa98)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818d17a9)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818d492c)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff818d91e6)
Location: include/linux/device.h:735
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818db725)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818dbeff)
Location: include/linux/device.h:735
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dd5fd)
Location: include/linux/device.h:735
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
In drivers/pci/pci.c (ffffffff8163489d)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81638b0b)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff81642135)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652060)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656e25)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff81658ca4)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff8179f0d0)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff817af11d)
Location: include/linux/device.h:741
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
In drivers/base/bus.c (ffffffff817b01e8)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/base/bus.c:device_reprobe
```
```
In drivers/base/dd.c (ffffffff817b2a6a)
Location: include/linux/device.h:741
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
In drivers/base/platform.c (ffffffff817b4722)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff817bd7a1)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817c4a58)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff818007b5)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81802fa8)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803761)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81806152)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c129)
Location: include/linux/device.h:741
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
In drivers/nvdimm/btt_devs.c (ffffffff818114ce)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811bf8)
Location: include/linux/device.h:741
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
In drivers/dax/bus.c (ffffffff81817dd1)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182cdf2)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81868cc5)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff818ab4ee)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff818b30c8)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818b4dc9)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff818b7efc)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff818bc36c)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff818beae0)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff818bf2fd)
Location: include/linux/device.h:741
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c096d)
Location: include/linux/device.h:741
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
In drivers/pci/pci.c (ffffffff816a498d)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8e3b)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff816b2e05)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3db0)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8da5)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff816cac44)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff818280c0)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff8183833f)
Location: include/linux/device.h:758
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
In drivers/base/bus.c (ffffffff81838d80)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8183bf08)
Location: include/linux/device.h:758
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
In drivers/base/platform.c (ffffffff8183d862)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_store
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81847b21)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff8184ee6f)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8188abb5)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8188d502)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e2a1)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890442)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896749)
Location: include/linux/device.h:758
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
In drivers/nvdimm/btt_devs.c (ffffffff8189b8be)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c228)
Location: include/linux/device.h:758
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
In drivers/dax/bus.c (ffffffff818a23fb)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b8bc2)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff818f87c5)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff8194046e)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81948518)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8194a2f6)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff8194d98c)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff81952326)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81955140)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8195595d)
Location: include/linux/device.h:758
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff819570ad)
Location: include/linux/device.h:758
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
In drivers/pci/pci.c (ffffffff817c6de5)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cbacb)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff817db7a5)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e98e0)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eeffc)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff817f11be)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff8196805b)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff8197a6b1)
Location: include/linux/device.h:833
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
In drivers/base/bus.c (ffffffff8197b2cb)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8197e3d4)
Location: include/linux/device.h:833
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
In drivers/base/driver.c (ffffffff8197ecac)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff819805bb)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff8198c6f9)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff819933ac)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff819d42c5)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff819d6a56)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d78b0)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da122)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0e23)
Location: include/linux/device.h:833
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
In drivers/nvdimm/btt_devs.c (ffffffff819e505e)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e5ab8)
Location: include/linux/device.h:833
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
In drivers/dax/bus.c (ffffffff819ebbea)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a044b2)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81a49c95)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81a9863e)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81aa0eb8)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81aa2f62)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa683b)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff81aab9c4)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81aaea69)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81aaf5fa)
Location: include/linux/device.h:833
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0d5a)
Location: include/linux/device.h:833
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
In drivers/pci/pci.c (ffffffff818e4285)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff818eabdf)
Location: include/linux/device.h:830
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
In drivers/pci/pcie/err.c (ffffffff818fd6d5)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff81919617)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/iommu/iommu.c (ffffffff81ad161b)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_store_type
```
```
In drivers/base/core.c (ffffffff81ae7521)
Location: include/linux/device.h:830
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
In drivers/base/bus.c (ffffffff81ae831b)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81aeb944)
Location: include/linux/device.h:830
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
In drivers/base/driver.c (ffffffff81aec384)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81aee0cb)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81afc299)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81b03a4f)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81b4eae5)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81b5175b)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b526e0)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b553e2)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5c8e3)
Location: include/linux/device.h:830
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
In drivers/nvdimm/btt_devs.c (ffffffff81b60e7e)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b619d8)
Location: include/linux/device.h:830
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
In drivers/dax/bus.c (ffffffff81b687db)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b830b2)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81bd0105)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81c1b502)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81c264d8)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c28a42)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2d62b)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff81c32ea4)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81c364c9)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81c3736b)
Location: include/linux/device.h:830
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c3901a)
Location: include/linux/device.h:830
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
In drivers/pci/pci.c (ffffffff81922ee8)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192e1af)
Location: include/linux/device.h:956
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
In drivers/pci/pcie/err.c (ffffffff81940b65)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff8195cc37)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/base/core.c (ffffffff81b3590b)
Location: include/linux/device.h:956
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
In drivers/base/bus.c (ffffffff81b35eb4)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81b39bb4)
Location: include/linux/device.h:956
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
In drivers/base/driver.c (ffffffff81b3a574)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81b3c45b)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a689)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81b51aaf)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81ba1f35)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4c05)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5ba0)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba8932)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bafeb3)
Location: include/linux/device.h:956
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
In drivers/nvdimm/btt_devs.c (ffffffff81bb43fe)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb4fd8)
Location: include/linux/device.h:956
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
In drivers/dax/bus.c (ffffffff81bbbc2e)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd6ddb)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81c27d85)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81c82432)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81c8d498)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_wireless_status_intf
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c8fa12)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81c9478b)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff81c9a178)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81c9d7b9)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81c9e6ab)
Location: include/linux/device.h:956
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ca03da)
Location: include/linux/device.h:956
Inline: True
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
In drivers/pci/pci.c (ffffffff8196b468)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976b2f)
Location: include/linux/device.h:988
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
In drivers/pci/pcie/aer.c (ffffffff81988c01)
Location: include/linux/device.h:988
Inline: True
```
```
In drivers/pci/pcie/err.c (ffffffff81989dc5)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (ffffffff819a6257)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
  - drivers/pci/iov.c:sriov_numvfs_show
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_msix_count_store
  - drivers/pci/iov.c:sriov_vf_total_msix_show
```
```
In drivers/base/core.c (ffffffff81b8d32b)
Location: include/linux/device.h:988
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
In drivers/base/bus.c (ffffffff81b8d8d4)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff81b91674)
Location: include/linux/device.h:988
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
In drivers/base/driver.c (ffffffff81b92034)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/driver.c:driver_set_override
  - drivers/base/driver.c:driver_set_override
```
```
In drivers/base/platform.c (ffffffff81b93fab)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
```
```
In drivers/base/power/sysfs.c (ffffffff81ba2a79)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81baa09f)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81bf60c5)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8e82)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9e20)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfcad2)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c042e3)
Location: include/linux/device.h:988
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
In drivers/nvdimm/btt_devs.c (ffffffff81c0894e)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c09558)
Location: include/linux/device.h:988
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
In drivers/dax/bus.c (ffffffff81c103b7)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:align_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_store
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:pgoff_show
  - drivers/dax/bus.c:end_show
  - drivers/dax/bus.c:start_show
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:delete_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_show
  - drivers/dax/bus.c:seed_show
  - drivers/dax/bus.c:available_size_show
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2ba35)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81cda395)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
```
```
In drivers/usb/core/hub.c (ffffffff81d36d72)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81d41fc8)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:__usb_wireless_status_intf
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff81d445c2)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
```
```
In drivers/usb/core/sysfs.c (ffffffff81d4924b)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff81d4ed48)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff81d52369)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff81d532ab)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5502a)
Location: include/linux/device.h:988
Inline: True
```
```
In net/devlink/core.c (ffffffff82101276)
Location: include/linux/device.h:988
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_pernet_pre_exit
```
```
In net/devlink/netlink.c (ffffffff82101954)
Location: include/linux/device.h:988
Inline: True
Inline callers:
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
In drivers/pci/pci.c (ffff8000106e326c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee37c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffff800010701154)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b500)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff80001071257c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffff800010716b70)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/amba/bus.c (ffff8000107b8b00)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/amba/bus.c:driver_override_store
  - drivers/amba/bus.c:driver_override_show
```
```
In drivers/base/core.c (ffff8000108e736c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffff8000108e8cc8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffff8000108eb280)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffff8000108edadc)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffff8000108f7774)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffff800010902c88)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffff800010950224)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffff800010952a80)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffff8000109532c0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffff800010956080)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095bb94)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffff800010960c24)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/scsi/scsi_scan.c (ffff80001097a938)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffff8000109c21dc)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffff800010a19a18)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffff800010a24920)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffff800010a26628)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffff800010a2a8d4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffff800010a314f8)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffff800010a34c3c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffff800010a35740)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a36e70)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (c087f118)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (c0889400)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (c0898e44)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/iov.c (c08a139c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/amba/bus.c (c08e4f80)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/amba/bus.c:driver_override_store
  - drivers/amba/bus.c:driver_override_show
```
```
In drivers/base/core.c (c09d5978)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (c09d7030)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (c09d93b0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (c09dba7c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (c09e362c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (c09ed0c8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/scsi/scsi_scan.c (c0a4e350)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (c0aaf0a8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (c0af1c84)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (c0afade0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (c0afc74c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (c0b00444)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (c0b051ec)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b08418)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (c0b08eb8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (c0b0a278)
Location: include/linux/device.h:1460
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
In arch/powerpc/kernel/eeh_driver.c (c00000000004a940)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
```
```
In drivers/pci/pci.c (c00000000085d160)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (c00000000086aa78)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/iov.c (c000000000886e24)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (c00000000097d658)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (c00000000097f690)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (c000000000982820)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (c000000000986068)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (c0000000009930f0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (c0000000009a1214)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (c0000000009fc730)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (c0000000009ffb54)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00714)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (c000000000a03d20)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0ca4c)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (c000000000a13fb0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a14ff4)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (c000000000a353f4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (c000000000a859a8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (c000000000ab162c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (c000000000ad2f78)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (c000000000adf758)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (c000000000ae1ce4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (c000000000ae72c8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (c000000000aee770)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c000000000af259c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (c000000000af37f8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (c000000000af5a0c)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffe0004baae6)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2c0a)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffe0004cfeb2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d813a)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/iov.c (ffffffe0004dff32)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffe00057bb36)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffe00057ceae)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffe00057ef20)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffe000580d50)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffe00058828c)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/nvdimm/core.c (ffffffe0005c04f8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffe0005c25f2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2c80)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c54b8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca10c)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffe0005ce5dc)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e1ac2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffe000615d6e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffe00063e548)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffe000646d2e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffe0006484fe)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffe00064c108)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffe00064fde0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffe000652552)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffe000652f8e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000654016)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffff81574c90)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d885)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8158d7d5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596470)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ca7a)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815a0534)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816c2147)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816c37b1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816c5764)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816c7b75)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816cefa1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816d85e8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff817048b5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81706ac9)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707275)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817096d2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e9b9)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffff81713b6e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817145e8)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (ffffffff8172aa32)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81776895)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/usb/core/hub.c (ffffffff817a25de)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817ac028)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817adb00)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817b1a25)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff817b5fc2)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817b8ffd)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817b97af)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817baa5d)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffff815633f0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c655)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8157c315)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81585600)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bc0a)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff8158f6c4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/acpi/nfit/core.c (ffffffff815f9455)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_shutdown
  - drivers/acpi/nfit/core.c:acpi_nfit_flush_probe
  - drivers/acpi/nfit/core.c:acpi_nvdimm_notify
  - drivers/acpi/nfit/core.c:scrub_show
  - drivers/acpi/nfit/core.c:hw_error_scrub_store
```
```
In drivers/base/core.c (ffffffff8169d3f7)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8169ea61)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816a09e4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816a2e75)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816aa2d1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff816b2c48)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff816d8335)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816da549)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dacf5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd152)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2439)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffff816e75ee)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8068)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (ffffffff81703e52)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff81756645)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff8177bd06)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff8179441e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff8179da28)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff8179f500)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817a3455)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff817a79e2)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817aaa2d)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817ab1df)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac47d)
Location: include/linux/device.h:1460
Inline: True
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184dab5)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffff815744c0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d745)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff8158d695)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815969b0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159cffa)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815a0ab4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff816f0617)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff816f1c81)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff816f3c34)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff816f60e5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff816fd511)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff81705f28)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff81743685)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81745899)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746045)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817484a2)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174d789)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffff8175293e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817533b8)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (ffffffff81769802)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817a6c35)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817c6ad6)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff817df07e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff817e8ac8)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff817ea5a0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817ee4c5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff817f2a62)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff817f5a9d)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff817f624f)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f74fd)
Location: include/linux/device.h:1460
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
In drivers/pci/pci.c (ffffffff8158e99b)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_lock
  - drivers/pci/pci.c:pci_reset_function
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597bf5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:driver_override_show
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/pcie/err.c (ffffffff815a7b45)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_slot_reset
  - drivers/pci/pcie/err.c:report_mmio_enabled
  - drivers/pci/pcie/err.c:report_error_detected
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0e30)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pci_dev_set_disconnected
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b742a)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/iov.c (ffffffff815baee4)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_numvfs_store
```
```
In drivers/base/core.c (ffffffff8170ae55)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_online
  - drivers/base/core.c:device_del
  - drivers/base/core.c:online_show
```
```
In drivers/base/bus.c (ffffffff8170c4c1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices_helper
```
```
In drivers/base/dd.c (ffffffff8170e464)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_driver_lock
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:coredump_store
```
```
In drivers/base/platform.c (ffffffff81710975)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/platform.c:driver_override_show
  - drivers/base/platform.c:driver_override_store
```
```
In drivers/base/power/sysfs.c (ffffffff81717da1)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/base/power/sysfs.c:control_store
```
```
In drivers/base/power/main.c (ffffffff817208f3)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:device_resume
```
```
In drivers/nvdimm/core.c (ffffffff8175ead5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81760cd9)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761485)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81763922)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81768c09)
Location: include/linux/device.h:1460
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
In drivers/nvdimm/btt_devs.c (ffffffff8176ddae)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176e828)
Location: include/linux/device.h:1460
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
In drivers/scsi/scsi_scan.c (ffffffff81784f72)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
```
```
In drivers/spi/spi.c (ffffffff817c0ab5)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
```
```
In drivers/vfio/vfio.c (ffffffff817e0d76)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/usb/core/hub.c (ffffffff817f936e)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_remote_wakeup
  - drivers/usb/core/hub.c:usb_authorize_device
  - drivers/usb/core/hub.c:usb_deauthorize_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/message.c (ffffffff81802d18)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_authorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
  - drivers/usb/core/message.c:usb_deauthorize_interface
```
```
In drivers/usb/core/driver.c (ffffffff818047e0)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_release_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81808705)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:remove_store
```
```
In drivers/usb/core/devio.c (ffffffff8180cce2)
Location: include/linux/device.h:1460
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
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffffffff8180fcdd)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/core/port.c (ffffffff8181048f)
Location: include/linux/device.h:1460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8181173d)
Location: include/linux/device.h:1460
Inline: True
```
</details>
</li>
</ul>

## Differences
