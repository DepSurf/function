# Function: <code>cpuhp_state_remove_instance_nocalls</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811ac426)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff81422a58)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In net/core/flow.c (ffffffff817cf193)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_fini
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
In kernel/padata.c (ffffffff811b3e26)
Location: include/linux/cpuhotplug.h:351
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff81432577)
Location: include/linux/cpuhotplug.h:351
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In net/core/flow.c (ffffffff817ee523)
Location: include/linux/cpuhotplug.h:351
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_fini
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
In kernel/padata.c (ffffffff811c7ab6)
Location: include/linux/cpuhotplug.h:379
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff8145e0fa)
Location: include/linux/cpuhotplug.h:379
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff811e7d01)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff81491a16)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff811f8c51)
Location: include/linux/cpuhotplug.h:384
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814ab468)
Location: include/linux/cpuhotplug.h:384
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In kernel/padata.c (ffffffff81210711)
Location: include/linux/cpuhotplug.h:389
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814d93ef)
Location: include/linux/cpuhotplug.h:389
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff8121d254)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814f27af)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff81249575)
Location: include/linux/cpuhotplug.h:396
Inline: True
Inline callers:
  - kernel/padata.c:__padata_free
  - kernel/padata.c:__padata_free
```
```
In block/blk-mq.c (ffffffff81550a01)
Location: include/linux/cpuhotplug.h:396
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff812539b5)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In fs/io-wq.c (ffffffff8139aec5)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
```
```
In block/blk-mq.c (ffffffff8156d141)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff81257fd5)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In fs/io-wq.c (ffffffff813a3a62)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
```
```
In block/blk-mq.c (ffffffff815773d0)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In drivers/iommu/iova.c (ffffffff817a3635)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In kernel/padata.c (ffffffff81293b45)
Location: include/linux/cpuhotplug.h:502
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In fs/io-wq.c (ffffffff813f3105)
Location: include/linux/cpuhotplug.h:502
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
```
```
In block/bio.c (ffffffff815c7b4e)
Location: include/linux/cpuhotplug.h:502
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff815dc130)
Location: include/linux/cpuhotplug.h:502
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In drivers/iommu/iova.c (ffffffff8182c865)
Location: include/linux/cpuhotplug.h:502
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In kernel/padata.c (ffffffff812e9985)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/bio.c (ffffffff8167287e)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff81683715)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In io_uring/io-wq.c (ffffffff816dbc6d)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff8196dd66)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d9453)
Location: include/linux/cpuhotplug.h:508
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
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
In kernel/padata.c (ffffffff813537a5)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/bio.c (ffffffff8172e33a)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff81740daa)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In io_uring/io-wq.c (ffffffff817a7d71)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff81ad8686)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b5450d)
Location: include/linux/cpuhotplug.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
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
In kernel/padata.c (ffffffff813849a5)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/bio.c (ffffffff8176a60a)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff8177d06a)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In io_uring/io-wq.c (ffffffff817e8c1f)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff81b265c6)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7a5d)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
```
In drivers/net/virtio_net.c (ffffffff81c542e5)
Location: include/linux/cpuhotplug.h:510
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
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
In kernel/padata.c (ffffffff813addb5)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/bio.c (ffffffff817aca6a)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
```
```
In block/blk-mq.c (ffffffff817bf3fa)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In io_uring/io-wq.c (ffffffff8182e9cf)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
```
```
In drivers/iommu/iova.c (ffffffff81b7d3e6)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbdc9)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
```
In drivers/net/virtio_net.c (ffffffff81d0aa25)
Location: include/linux/cpuhotplug.h:495
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
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
In kernel/padata.c (ffff8000102a8e1c)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffff8000105f2220)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In drivers/perf/arm-ccn.c (ffff800010b922a4)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/arm_pmu.c (ffff800010b956a4)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_register
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
In arch/arm/mach-imx/mmdc.c (c03333c0)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_remove
```
```
In kernel/padata.c (c04d7ffc)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (c079e144)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In drivers/perf/arm-ccn.c (c0c7be3c)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/arm_pmu.c (c0c7ec4c)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_register
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
In kernel/padata.c (c00000000035d164)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (c000000000789374)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430b46)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff812158a4)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814ead8f)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff81208604)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814db2df)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff81213644)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814e6e1f)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
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
In kernel/padata.c (ffffffff81222a64)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
```
```
In block/blk-mq.c (ffffffff814ffe17)
Location: include/linux/cpuhotplug.h:390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
</details>
</li>
</ul>

## Differences
