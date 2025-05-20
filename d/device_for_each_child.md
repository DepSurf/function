# Function: <code>device_for_each_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815469c0)
Location: drivers/base/core.c:1387
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/base/core.c:device_offline
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:nvdimm_bus_unregister
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_clients_command
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
**Symbols:**

```
ffffffff815469c0-ffffffff81546a4a: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598640)
Location: drivers/base/core.c:1387
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_offline
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/i2c/i2c-core.c:i2c_clients_command
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff81598640-ffffffff815986ca: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6220)
Location: drivers/base/core.c:1978
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_offline
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/i2c/i2c-core.c:i2c_clients_command
  - drivers/i2c/i2c-core.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff815c6220-ffffffff815c62aa: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db090)
Location: drivers/base/core.c:1976
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_mmio_enabled
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_error_detected
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff815db090-ffffffff815db11a: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642050)
Location: drivers/base/core.c:2111
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff81642050-ffffffff816420dc: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d2e0)
Location: drivers/base/core.c:2158
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff8167d2e0-ffffffff8167d36a: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169cc70)
Location: drivers/base/core.c:2233
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff8169cc70-ffffffff8169ccfa: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5a50)
Location: drivers/base/core.c:2459
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/soundwire/bus.c:sdw_delete_bus_master
```
**Symbols:**

```
ffffffff816d5a50-ffffffff816d5ae5: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9840)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff816f9840-ffffffff816f98d5: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5189)
Location: drivers/base/core.c:2997
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff817b2820-ffffffff817b28b5: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9879)
Location: drivers/base/core.c:3409
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff817c7280-ffffffff817c7315: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ad069)
Location: drivers/base/core.c:3636
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff817aa6f0-ffffffff817aa785: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81836359)
Location: drivers/base/core.c:3701
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff818338b0-ffffffff81833945: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81978339)
Location: drivers/base/core.c:3735
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/acpi/bus.c:acpi_dev_for_each_child
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff81975040-ffffffff819750ec: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae4b99)
Location: drivers/base/core.c:3934
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_port_device_suspend
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/acpi/bus.c:acpi_dev_for_each_child
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff81ae0800-ffffffff81ae08ac: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b32f29)
Location: drivers/base/core.c:3943
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_port_device_suspend
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/acpi/bus.c:acpi_dev_for_each_child
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_block_targets
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff81b2ea20-ffffffff81b2eacc: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a839)
Location: drivers/base/core.c:3956
Inline: True
Inline callers:
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/core.c:device_is_dependent
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_port_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv.c:pcie_port_device_suspend
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/acpi/bus.c:acpi_dev_for_each_child
  - drivers/pmdomain/governor.c:default_suspend_ok
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_block_targets
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff81b86220-ffffffff81b862cc: device_for_each_child (STB_GLOBAL)
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
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3c78)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
**Symbols:**

```
ffff8000108e3c78-ffff8000108e3d28: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d27a8)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_remove
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
c09d27a8-c09d2858: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000978d20)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_transport_srp.c:srp_remove_host
  - drivers/scsi/scsi_transport_srp.c:srp_timed_out
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
c000000000978d20-c000000000978e20: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000578df2)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffe000578df2-ffffffe000578e5c: device_for_each_child (STB_GLOBAL)
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
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf030)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff816bf030-ffffffff816bf0c5: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a2e0)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
```
**Symbols:**

```
ffffffff8169a2e0-ffffffff8169a375: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed500)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
```
**Symbols:**

```
ffffffff816ed500-ffffffff816ed595: device_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_for_each_child(struct device *parent, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707d40)
Location: drivers/base/core.c:2496
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_device
  - drivers/pci/pcie/portdrv_core.c:pcie_port_find_service
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_runtime_suspend
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_resume_noirq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_err_resume
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/virtio/virtio_mmio.c:vm_cmdline_get
  - drivers/base/core.c:device_reorder_to_tail
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/domain_governor.c:default_suspend_ok
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/da903x.c:da903x_remove
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_ns_forget_poison_check
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/dimm_devs.c:nvdimm_bus_check_dimm_count
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_conflict
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/i2c/i2c-core-base.c:i2c_clients_command
  - drivers/i2c/i2c-core-base.c:i2c_check_addr_busy
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-core-base.c:i2c_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/i2c/i2c-dev.c:i2cdev_check_mux_parents
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_stop
```
**Symbols:**

```
ffffffff81707d40-ffffffff81707dd5: device_for_each_child (STB_GLOBAL)
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
