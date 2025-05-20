# Function: <code>ida_simple_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eaed0)
Location: lib/idr.c:1078
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:memcg_activate_kmem
  - fs/kernfs/dir.c:__kernfs_new_node
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/core.c:__nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:rtc_device_register
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff813eaed0-ffffffff813eafcb: ida_simple_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81431250)
Location: lib/idr.c:1078
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/kernfs/dir.c:__kernfs_new_node
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:rtc_device_register
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff81431250-ffffffff8143134b: ida_simple_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144d4c0)
Location: lib/idr.c:1084
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/kernfs/dir.c:__kernfs_new_node
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:rtc_device_register
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
```
**Symbols:**

```
ffffffff8144d4c0-ffffffff8144d5bb: ida_simple_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ed170)
Location: lib/idr.c:425
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/kernfs/dir.c:__kernfs_new_node
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff818ed170-ffffffff818ed26b: ida_simple_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81973190)
Location: lib/idr.c:433
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff81973190-ffffffff8197328b: ida_simple_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ida_simple_get(struct ida *ida, unsigned int start, unsigned int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf720)
Location: lib/idr.c:563
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/proc/generic.c:proc_register
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/tty/serdev/core.c:serdev_controller_alloc
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/base/platform.c:platform_device_add
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
  - drivers/dax/super.c:alloc_dax
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/input/input.c:input_get_new_minor
  - drivers/input/input.c:input_get_new_minor
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff819cf720-ffffffff819cf80e: ida_simple_get (STB_GLOBAL)
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
