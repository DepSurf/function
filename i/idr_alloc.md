# Function: <code>idr_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813eaa70)
Location: lib/idr.c:450
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:init_workqueues
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core.c:i2c_add_adapter
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/core/net_namespace.c:__peernet2id_alloc
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff813eaa70-ffffffff813eab7f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430df0)
Location: lib/idr.c:450
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core.c:i2c_add_adapter
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81430df0-ffffffff81430ef6: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144cfc0)
Location: lib/idr.c:450
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core.c:i2c_add_adapter
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/thermal/thermal_core.c:get_idr
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff8144cfc0-ffffffff8144d109: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ec930)
Location: lib/idr.c:29
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
```
**Symbols:**

```
ffffffff818ec930-ffffffff818ec9d8: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a78d7)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/cgroup/cgroup.c (ffffffff8112e4c4)
Location: include/linux/idr.h:108
Inline: True
```
```
In kernel/events/core.c (ffffffff811b90b1)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/shmem.c (ffffffff811ed02a)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/memcontrol.c (ffffffff8198a52a)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In ipc/util.c (ffffffff813a7153)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814647e0)
Location: include/linux/idr.h:108
Inline: True
```
```
In block/bsg.c (ffffffff81470d2d)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f9d9)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
```
```
In drivers/iommu/intel-svm.c (ffffffff8163afe9)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/block/loop.c (ffffffff8166ff45)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
```
```
In drivers/scsi/sg.c (ffffffff816cb46c)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/spi/spi.c (ffffffff816f68b2)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817061f8)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hcd.c (ffffffff8171c1c4)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81792e8c)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
```
In drivers/md/dm.c (ffffffff817c10fd)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
```
In drivers/powercap/powercap_sys.c (ffffffff81819f07)
Location: include/linux/idr.h:108
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183c8fe)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
```
In net/netlink/genetlink.c (ffffffff8188af85)
Location: include/linux/idr.h:108
Inline: True
```
```
In lib/idr.c (ffffffff81973308)
Location: include/linux/idr.h:108
Inline: True
Inline callers:
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
```
**Symbols:**

```
ffffffff810a44f0-ffffffff810a4548: idr_alloc.constprop.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cee20)
Location: lib/idr.c:82
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff819cee20-ffffffff819cee7e: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a082c0)
Location: lib/idr.c:78
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a082c0-ffffffff81a0831e: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77c10)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a77c10-ffffffff81a77c6f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf000)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81aaf000-ffffffff81aaf05f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8d30)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/io_uring.c:io_provide_buffers
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815e8d30-ffffffff815e8d8f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160dde0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/io_uring.c:io_provide_buffers
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8160dde0-ffffffff8160de3f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1530)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff815f1530-ffffffff815f158c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e6a0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8165e6a0-ffffffff8165e6fc: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81777eb0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81777eb0-ffffffff81777f1c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020bc0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff82020bc0-ffffffff82020c2c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0be0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff820a0be0-ffffffff820a0c4c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178bc0)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - mm/shrinker.c:shrinker_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - drivers/pwm/core.c:__pwmchip_add
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_alloc
  - drivers/gpu/drm/drm_auth.c:drm_getmagic
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
  - drivers/gpu/drm/drm_drv.c:drm_minor_alloc
  - drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
  - drivers/gpu/drm/drm_lease.c:fill_object_idr
  - drivers/gpu/drm/drm_lease.c:fill_object_idr
  - drivers/gpu/drm/drm_lease.c:fill_object_idr
  - drivers/gpu/drm/drm_lease.c:drm_lease_create
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_object_add
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
  - drivers/accel/drm_accel.c:accel_minor_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff82178bc0-ffffffff82178c2c: idr_alloc (STB_GLOBAL)
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
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88800)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_register
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffff800010d88800-ffff800010d8887c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83698)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_register
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
c0e83698-c0e8374c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec8f60)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
c000000000ec8f60-c000000000ec902c: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b27e2)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/of/overlay.c:init_overlay_changeset
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffe0008b27e2-ffffffe0008b2828: idr_alloc (STB_GLOBAL)
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
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4de50)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a4de50-ffffffff81a4deaf: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0af40)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81a0af40-ffffffff81a0af9f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba240)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81aba240-ffffffff81aba29f: idr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int idr_alloc(struct idr *idr, void *ptr, int start, int end, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac6690)
Location: lib/idr.c:79
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
```
**Symbols:**

```
ffffffff81ac6690-ffffffff81ac66ef: idr_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
