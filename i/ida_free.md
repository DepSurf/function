# Function: <code>ida_free</code>

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
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a087c0)
Location: lib/idr.c:482
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_i_callback
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:delete_ptp_clock
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
```
**Symbols:**

```
ffffffff81a087c0-ffffffff81a088ec: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a78170)
Location: lib/idr.c:493
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:delete_ptp_clock
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a78170-ffffffff81a7829b: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf430)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81aaf430-ffffffff81aaf55b: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e92d0)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_alloc_cache_id
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-sysfs.c:__blk_release_queue
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff815e92d0-ffffffff815e93fe: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e380)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memcontrol.c:memcg_online_kmem
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/genhd.c:disk_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:delete_store
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8160e380-ffffffff8160e4ae: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1ad0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memcontrol.c:memcg_online_kmem
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/genhd.c:disk_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:delete_store
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - drivers/net/wwan/wwan_core.c:wwan_dev_destroy
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff815f1ad0-ffffffff815f1bfe: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_online_kmem
  - mm/memcontrol.c:memcg_online_kmem
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_device_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:delete_store
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_dev_destroy
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81cdf24d-ffffffff81cdf287: ida_free.cold (STB_LOCAL)
ffffffff8165ec30-ffffffff8165ed7e: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_device_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:delete_store
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_dev_destroy
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ea5a21-ffffffff81ea5a5c: ida_free.cold (STB_LOCAL)
ffffffff817784f0-ffffffff8177864c: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:unregister_trace_event
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_device_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:delete_store
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_dev_destroy
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff820b7462-ffffffff820b749d: ida_free.cold (STB_LOCAL)
ffffffff82021290-ffffffff820213f0: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:unregister_trace_event
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_device_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodev_release
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/iommu/iommu-sva.c:mm_pasid_drop
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/soc.c:soc_release
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_free_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:__free_dev_dax_id
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/net/wwan/wwan_core.c:wwan_dev_destroy
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_release
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff821387ea-ffffffff82138825: ida_free.cold (STB_LOCAL)
ffffffff820a12c0-ffffffff820a1420: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/idr.c (0)
Location: lib/idr.c:487
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - kernel/trace/trace_output.c:unregister_trace_event
  - fs/super.c:kill_litter_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:do_eventfd
  - fs/eventfd.c:eventfd_release
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_device_release
  - lib/memregion.c:memregion_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodev_release
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_device_remove
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
  - drivers/char/misc.c:misc_register
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:init_port_console
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/iommu.c:iommu_free_global_pasid
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:software_node_release
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/soc.c:soc_release
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_free_disk
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/dax/bus.c:dax_mapping_release
  - drivers/dax/bus.c:__free_dev_dax_id
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/gpu/drm/drm_connector.c:__drm_connector_init
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_release
  - drivers/thermal/thermal_core.c:thermal_unbind_cdev_from_trip
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_put_umem
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8221a784-ffffffff8221a7bf: ida_free.cold (STB_LOCAL)
ffffffff821792a0-ffffffff82179409: ida_free (STB_GLOBAL)
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
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d89278)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/soc.c:soc_device_unregister
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_rpmb_device_release
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
  - drivers/firmware/arm_scmi/bus.c:scmi_device_destroy
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffff800010d89278-ffff800010d8943c: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83bd8)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/soc.c:soc_device_unregister
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_rpmb_device_release
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
  - drivers/firmware/arm_scmi/bus.c:scmi_device_destroy
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c0e83bd8-c0e83d40: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9810)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/mmu_context.c:destroy_context
  - arch/powerpc/mm/book3s64/mmu_context.c:__destroy_context
  - arch/powerpc/mm/book3s64/mmu_context.c:init_new_context
  - arch/powerpc/platforms/powernv/vas-window.c:vas_window_alloc
  - arch/powerpc/platforms/powernv/vas-window.c:vas_window_free
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/soc.c:soc_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c000000000ec9810-c000000000ec99f0: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2b0c)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_rpmb_device_release
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_put
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe0008b2b0c-ffffffe0008b2c56: ida_free (STB_GLOBAL)
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
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e280)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_release_subsystem
  - drivers/nvme/host/core.c:nvme_free_ns_head
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a4e280-ffffffff81a4e3ab: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b370)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/core.c:nvme_free_ctrl
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_release_subsystem
  - drivers/nvme/host/core.c:nvme_free_ns_head
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a0b370-ffffffff81a0b49b: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba670)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81aba670-ffffffff81aba79b: ida_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ida_free(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac6ac0)
Location: lib/idr.c:484
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/super.c:kill_anon_super
  - fs/namespace.c:cleanup_group_ids
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/eventfd.c:eventfd_free_ctx
  - fs/proc/generic.c:proc_register
  - fs/devpts/inode.c:devpts_kill_index
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/namespace_devs.c:namespace_pmem_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:dax_free_inode
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/sd.c:scsi_disk_release
  - drivers/scsi/sd.c:sd_probe
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_release
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_release
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/sock_reuseport.c:reuseport_free_rcu
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ac6ac0-ffffffff81ac6beb: ida_free (STB_GLOBAL)
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
