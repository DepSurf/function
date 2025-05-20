# Function: <code>ida_simple_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eafd0)
Location: lib/idr.c:1123
Inline: True
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:worker_thread
  - mm/memcontrol.c:memcg_activate_kmem
  - mm/memcontrol.c:mem_cgroup_css_offline
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_device_del
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/core.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:rtc_device_release
  - drivers/rtc/class.c:rtc_device_register
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
```
**Symbols:**

```
ffffffff813eafd0-ffffffff813eb013: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81431350)
Location: lib/idr.c:1123
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_del
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
  - drivers/base/platform-msi.c:platform_msi_domain_free_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:namespace_blk_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_release
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81431350-ffffffff81431393: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144d5c0)
Location: lib/idr.c:1134
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_del
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
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
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_release
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8144d5c0-ffffffff8144d603: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ed270)
Location: lib/idr.c:475
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/proc/generic.c:pde_put
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
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
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff818ed270-ffffffff818ed2b3: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81973290)
Location: lib/idr.c:483
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/proc/generic.c:pde_put
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
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
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_release
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:watchdog_unregister_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - drivers/nvmem/core.c:nvmem_release
```
**Symbols:**

```
ffffffff81973290-ffffffff819732d3: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ida_simple_remove(struct ida *ida, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf810)
Location: lib/idr.c:613
Inline: True
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/proc/generic.c:proc_register
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/phy/phy-core.c:phy_release
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_ctrl_release
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
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
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/input/input.c:input_free_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
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
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
```
**Symbols:**

```
ffffffff819cf810-ffffffff819cf84a: ida_simple_remove (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
