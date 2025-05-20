# Function: <code>ida_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ida_init(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea3d0)
Location: lib/idr.c:1141
Inline: False
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_mount
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
**Symbols:**

```
ffffffff813ea3d0-ffffffff813ea421: ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ida_init(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430780)
Location: lib/idr.c:1141
Inline: False
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_mount
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
**Symbols:**

```
ffffffff81430780-ffffffff814307d1: ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ida_init(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c950)
Location: lib/idr.c:1152
Inline: False
Direct callers:
  - kernel/workqueue.c:init_worker_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
**Symbols:**

```
ffffffff8144c950-ffffffff8144c9a1: ida_init (STB_GLOBAL)
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
In kernel/workqueue.c (ffffffff810a0cc7)
Location: include/linux/idr.h:195
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/kernfs/dir.c (ffffffff812dae70)
Location: include/linux/idr.h:195
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff812e2171)
Location: include/linux/idr.h:195
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff8163185f)
Location: include/linux/idr.h:195
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff8172e6fd)
Location: include/linux/idr.h:195
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
In kernel/workqueue.c (ffffffff810a7519)
Location: include/linux/idr.h:259
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81306b51)
Location: include/linux/idr.h:259
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a1a3)
Location: include/linux/idr.h:259
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff8179fd3d)
Location: include/linux/idr.h:259
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
In kernel/workqueue.c (ffffffff810ae0ad)
Location: include/linux/idr.h:237
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81334b46)
Location: include/linux/idr.h:237
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d64d9)
Location: include/linux/idr.h:237
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff817e731a)
Location: include/linux/idr.h:237
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
In kernel/workqueue.c (ffffffff810b71dd)
Location: include/linux/idr.h:292
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff8134be91)
Location: include/linux/idr.h:292
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816aa9a6)
Location: include/linux/idr.h:292
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f828c)
Location: include/linux/idr.h:292
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff8181359a)
Location: include/linux/idr.h:292
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
In kernel/workqueue.c (ffffffff810ba768)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81374861)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816e40ad)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731950)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff81856346)
Location: include/linux/idr.h:309
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
In kernel/workqueue.c (ffffffff810c32b8)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff8138cae1)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff8170813d)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755ac0)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff818879b1)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810cad4c)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff813d7fcb)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/dma/dmaengine.c (ffffffff817082d3)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/swnode.c (ffffffff817c2eac)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff8181399f)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff81956991)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810c5e7c)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff813e9c6b)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff816a8f53)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff817254f3)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/swnode.c (ffffffff817d7cef)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822b8f)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff81834aee)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/thermal/thermal_core.c (ffffffff8195aad1)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810c77bc)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff813f06c1)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff8168b703)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81706793)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/base/swnode.c (ffffffff817bb893)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81805b3f)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff81817cbe)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/thermal/thermal_core.c (ffffffff8193f87a)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810da51c)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff814425b1)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff81700806)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81782053)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f4e7)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff818457a3)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890c01)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff818a230e)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/thermal/thermal_core.c (ffffffff819e416a)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810f3c4c)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff814be331)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff8182e486)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff818b8a66)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/virtio-iommu.c (ffffffff819706d7)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81989a63)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da901)
Location: include/linux/idr.h:312
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819ebb18)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/vfio/vfio.c (ffffffff834bcd35)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81b49338)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff81115e8c)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81556111)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff819619f5)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a05f65)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb4f7)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81af8da3)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55cd9)
Location: include/linux/idr.h:312
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b686e4)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce09a1)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In kernel/workqueue.c (ffffffff81122c2b)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff8158dec1)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff819a7e05)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a4ee25)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81ac4256)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b297b7)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81b472d2)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9229)
Location: include/linux/idr.h:312
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbbb50)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48b77)
Location: include/linux/idr.h:312
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In kernel/workqueue.c (ffffffff8112cbf8)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff815c6c30)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In drivers/acpi/scan.c (ffffffff819f0824)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a9aac5)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81b17125)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b807a7)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81b9f661)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd56a)
Location: include/linux/idr.h:314
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c102c1)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8869f)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_ida_init
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca2d14)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff03a)
Location: include/linux/idr.h:314
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In kernel/workqueue.c (ffff800010121038)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffff80001045e6b0)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbeec)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffff8000108f5c68)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffff800010956d10)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5484)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (c0374fa8)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (c061f114)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (c09e2178)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/thermal/thermal_core.c (c0bb474c)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In arch/powerpc/platforms/powernv/vas.c (c0000000000e1378)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
```
```
In kernel/workqueue.c (c00000000016a59c)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (c00000000057a6ac)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (c000000000990c18)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (c000000000a04aec)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (c000000000bbb2b4)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffe0000d9f8a)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffe0002ee372)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffe000586d7c)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5e38)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffe0006d058e)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810bd628)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff813850c1)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816cd88d)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a1b0)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvme/host/core.c (ffffffff817469df)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d831)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810abe58)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81375b51)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816a8bbd)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddc30)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvme/host/core.c (ffffffff8172865f)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4ec1)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810bcb88)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff81382b91)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816fbdfd)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81748f80)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff8187ce61)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In kernel/workqueue.c (ffffffff810c4f08)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/devpts/inode.c (ffffffff813966b1)
Location: include/linux/idr.h:309
Inline: True
```
```
In drivers/base/swnode.c (ffffffff817168dd)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764400)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/thermal/thermal_core.c (ffffffff81898891)
Location: include/linux/idr.h:309
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
</ul>
