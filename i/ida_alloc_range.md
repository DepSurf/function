# Function: <code>ida_alloc_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a088f0)
Location: lib/idr.c:377
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
```
**Symbols:**

```
ffffffff81a088f0-ffffffff81a08c90: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:388
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81a7864e-ffffffff81a7866f: ida_alloc_range.cold (STB_LOCAL)
ffffffff81a782a0-ffffffff81a7864e: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf560)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81aaf560-ffffffff81aaf90c: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e9400)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_alloc_cache_id
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:__blk_alloc_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff815e9400-ffffffff815e97bc: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e4b0)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8160e4b0-ffffffff8160e874: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1c00)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff815f1c00-ffffffff815f2006: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165ed80)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8165ed80-ffffffff8165f1b1: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778650)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/platform-msi.c:platform_msi_alloc_priv_data
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81778650-ffffffff81778a89: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82021400)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:register_trace_event
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/platform-msi.c:platform_msi_alloc_priv_data
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff82021400-ffffffff82021821: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a1430)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:register_trace_event
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/platform-msi.c:platform_msi_alloc_priv_data
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff820a1430-ffffffff820a1867: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82179420)
Location: lib/idr.c:380
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:register_trace_event
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_register_queue
  - lib/memregion.c:memregion_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/iommu.c:iommu_alloc_global_pasid
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/platform-msi.c:platform_msi_alloc_priv_data
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/nvmem/core.c:nvmem_register
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff82179420-ffffffff821798e3: ida_alloc_range (STB_GLOBAL)
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
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88e18)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffff800010d88e18-ffff800010d89274: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83d40)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
c0e83d40-c0e84120: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec99f0)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/mmu_context.c:init_new_context
  - arch/powerpc/mm/book3s64/mmu_context.c:hash__alloc_context_id
  - arch/powerpc/mm/book3s64/mmu_context.c:hash__alloc_context_id
  - arch/powerpc/mm/book3s64/mmu_context.c:hash__reserve_context_id
  - arch/powerpc/platforms/powernv/vas-window.c:vas_window_alloc
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
c000000000ec99f0-c000000000ec9eec: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2c56)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffe0008b2c56-ffffffe0008b2fc0: ida_alloc_range (STB_GLOBAL)
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
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e3b0)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81a4e3b0-ffffffff81a4e75c: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b4a0)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81a0b4a0-ffffffff81a0b84c: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba7a0)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81aba7a0-ffffffff81abab4c: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ida_alloc_range(struct ida *ida, unsigned int min, unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac6bf0)
Location: lib/idr.c:379
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:get_anon_bdev
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_new_index
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:swnode_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sd.c:sd_probe
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_get_id
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81ac6bf0-ffffffff81ac6f9c: ida_alloc_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
