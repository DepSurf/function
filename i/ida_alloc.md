# Function: <code>ida_alloc</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2a0c)
Location: include/linux/idr.h:253
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff81602ab1)
Location: include/linux/idr.h:253
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffff81721a40)
Location: include/linux/idr.h:253
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff812efbdd)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff816352c1)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffff8175fe96)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff813016ad)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff81656fdd)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffffffff81712b44)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff81783df6)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff8133a76d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In lib/memregion.c (ffffffff815e3f30)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/dma/dmaengine.c (ffffffff8170828f)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/base/power/wakeup.c (ffffffff817ce824)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff81847d66)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In net/core/sock_reuseport.c (ffffffff81a34da4)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_alloc
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
In fs/namespace.c (ffffffff8134637d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In lib/memregion.c (ffffffff81608463)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff816389f1)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/dmaengine.c (ffffffff817254af)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/base/platform.c (ffffffff817d07f3)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff817e2ee4)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff81834a08)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/sd.c (ffffffff818579b6)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/nvmem/core.c (ffffffff819da640)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81a370e4)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_alloc
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
In fs/namespace.c (ffffffff8134c78d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In lib/memregion.c (ffffffff815eb0c3)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8161c508)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/dmaengine.c (ffffffff8170674f)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/base/platform.c (ffffffff817b4213)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff817c72a4)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff81817bd8)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/sd.c (ffffffff8183a938)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff818882b4)
Location: include/linux/idr.h:271
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff819c0077)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81a1e244)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_alloc
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
In kernel/workqueue.c (ffffffff810d7e41)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
```
In fs/namespace.c (ffffffff8139a60d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In lib/memregion.c (ffffffff816575c3)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff8168ba28)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/dma/dmaengine.c (ffffffff8178200f)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/base/platform.c (ffffffff8183db42)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff81851684)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff818a2228)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/sd.c (ffffffff818c6ff1)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a421)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
```
```
In drivers/nvmem/core.c (ffffffff81a6f7c7)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81ad2207)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
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
In kernel/workqueue.c (ffffffff810f005c)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
```
In fs/namespace.c (ffffffff8141d338)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In lib/memregion.c (ffffffff8176eec3)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8e34)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/acpi/scan.c (ffffffff8182e2dd)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff818b8a40)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/virtio/virtio.c (ffffffff818bc8a5)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:register_virtio_device
```
```
In drivers/base/platform.c (ffffffff81980806)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff819974a2)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff819eba2b)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/sd.c (ffffffff81a13cdb)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f75d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
```
```
In drivers/hwmon/hwmon.c (ffffffff81b456b0)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/nvmem/core.c (ffffffff81be0bb0)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81c4fbfc)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
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
In kernel/workqueue.c (ffffffff81111a1c)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
```
In fs/namespace.c (ffffffff814a9688)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In block/blk-core.c (ffffffff81735421)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In lib/memregion.c (ffffffff8189e833)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff818c173c)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/acpi/scan.c (ffffffff8196181a)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a05f3f)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/virtio/virtio.c (ffffffff81a0b5c5)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:register_virtio_device
```
```
In drivers/iommu/iommu.c (ffffffff81acdef4)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/platform.c (ffffffff81aee2fe)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b08482)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff81b685ef)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/hosts.c (ffffffff81b76734)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
```
```
In drivers/scsi/sd.c (ffffffff81b940b6)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c0258d)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
```
```
In drivers/rtc/class.c (ffffffff81cb9a2a)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdc88c)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce09c5)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76e61)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/nvmem/core.c (ffffffff81d8c460)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81e04e49)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/xdp/xdp_umem.c (ffffffff81ff082b)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/workqueue.c (ffffffff8111e48c)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
```
In fs/namespace.c (ffffffff814de5d8)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In block/blk-core.c (ffffffff817719a1)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In lib/memregion.c (ffffffff818e0e03)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/gpio/gpiolib.c (ffffffff81904695)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/acpi/scan.c (ffffffff819a7c2a)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a4edff)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/virtio/virtio.c (ffffffff81a54455)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:register_virtio_device
```
```
In drivers/iommu/iommu.c (ffffffff81b1ca84)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/platform.c (ffffffff81b3c6a1)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b564b2)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/dax/bus.c (ffffffff81bbbbe0)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/hosts.c (ffffffff81bca3b4)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
```
```
In drivers/scsi/sd.c (ffffffff81bea606)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c67aed)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
```
```
In drivers/rtc/class.c (ffffffff81d2115a)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/hwmon/hwmon.c (ffffffff81d44d5a)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48b83)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4da1)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/extcon/extcon.c (ffffffff81df3161)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/nvmem/core.c (ffffffff81dfaaf0)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81e77699)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/xdp/xdp_umem.c (ffffffff8206c9db)
Location: include/linux/idr.h:271
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/workqueue.c (ffffffff81128eb4)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - kernel/workqueue.c:create_worker
```
```
In fs/namespace.c (ffffffff81511068)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/eventfd.c (ffffffff815579c0)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In block/blk-core.c (ffffffff817b3ce2)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In lib/memregion.c (ffffffff81927973)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - lib/memregion.c:memregion_alloc
```
```
In drivers/phy/phy-core.c (ffffffff81932079)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
```
```
In drivers/gpio/gpiolib.c (ffffffff8194c0dc)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/acpi/scan.c (ffffffff819f061a)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a9aa9f)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/virtio/virtio.c (ffffffff81aa50f5)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:register_virtio_device
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f73c)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/iommu/iommu.c (ffffffff81b72fa3)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/base/platform.c (ffffffff81b941fc)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/base/swnode.c (ffffffff81b9f5e0)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/base/power/wakeup.c (ffffffff81baeaa2)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/base/soc.c (ffffffff81bcc498)
Location: include/linux/idr.h:273
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf74e2)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_register
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa5f7)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04b48)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08e53)
Location: include/linux/idr.h:273
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0aa58)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81c0af68)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
```
```
In drivers/dax/bus.c (ffffffff81c10369)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
```
```
In drivers/scsi/hosts.c (ffffffff81c1efe4)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
```
```
In drivers/scsi/sd.c (ffffffff81c3fc55)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/rtc/class.c (ffffffff81dd6eba)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfb8b6)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff083)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ae91)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/extcon/extcon.c (ffffffff81ea97af)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/nvmem/core.c (ffffffff81eb1b6f)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock_reuseport.c (ffffffff81f37659)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/xdp/xdp_umem.c (ffffffff8214082e)
Location: include/linux/idr.h:273
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In fs/namespace.c (ffff8000103b3da8)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffff8000107fd278)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffff8000109036e0)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffff80001098a5d8)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (c0592cb0)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (c091e900)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (c09edad4)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (c0a5c818)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (c0000000004afb14)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (c0000000008c84c4)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (c0000000009a3018)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (c000000000a4adac)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffe00027762e)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffe000516f2c)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/scsi/sd.c (ffffffe0005ee9b2)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff812f9c8d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff8161ce7d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffffffff816d8ee4)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff817384e6)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff812ea8ad)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff8161156d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffffffff816b3504)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff8171a186)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff812f7a7d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff8164ae1d)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffffffff81706804)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff81778c76)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In fs/namespace.c (ffffffff81308dbd)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - fs/namespace.c:alloc_vfsmnt
```
```
In drivers/dma/dmaengine.c (ffffffff816653bd)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/power/wakeup.c (ffffffff81721214)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/scsi/sd.c (ffffffff81792a96)
Location: include/linux/idr.h:270
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
</li>
</ul>

## Differences
