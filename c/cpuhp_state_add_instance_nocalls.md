# Function: <code>cpuhp_state_add_instance_nocalls</code>

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
In kernel/padata.c (ffffffff811acb8b)
Location: include/linux/cpuhotplug.h:245
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
```
```
In block/blk-mq.c (ffffffff81422776)
Location: include/linux/cpuhotplug.h:245
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432306)
Location: include/linux/cpuhotplug.h:269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145de4e)
Location: include/linux/cpuhotplug.h:297
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491774)
Location: include/linux/cpuhotplug.h:296
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab1f5)
Location: include/linux/cpuhotplug.h:302
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d92ea)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f26aa)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e945)
Location: include/linux/cpuhotplug.h:314
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
In fs/io-wq.c (ffffffff8139c57d)
Location: include/linux/cpuhotplug.h:319
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In block/blk-mq.c (ffffffff8156ae25)
Location: include/linux/cpuhotplug.h:319
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
In fs/io-wq.c (ffffffff813a36d0)
Location: include/linux/cpuhotplug.h:327
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In block/blk-mq.c (ffffffff81577282)
Location: include/linux/cpuhotplug.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In drivers/iommu/iova.c (ffffffff817a3b5c)
Location: include/linux/cpuhotplug.h:327
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
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
In fs/io-wq.c (ffffffff813f2bb8)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In block/bio.c (ffffffff815c7e74)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/blk-mq.c (ffffffff815dbfe2)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In drivers/iommu/iova.c (ffffffff8182cdc3)
Location: include/linux/cpuhotplug.h:401
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
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
In block/bio.c (ffffffff81672bac)
Location: include/linux/cpuhotplug.h:407
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/blk-mq.c (ffffffff8168360d)
Location: include/linux/cpuhotplug.h:407
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In io_uring/io-wq.c (ffffffff816db711)
Location: include/linux/cpuhotplug.h:407
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff8196e1af)
Location: include/linux/cpuhotplug.h:407
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d92d2)
Location: include/linux/cpuhotplug.h:407
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
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
In block/bio.c (ffffffff8172e66c)
Location: include/linux/cpuhotplug.h:411
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/blk-mq.c (ffffffff81740c9d)
Location: include/linux/cpuhotplug.h:411
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In io_uring/io-wq.c (ffffffff817a77fd)
Location: include/linux/cpuhotplug.h:411
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff81ad8b14)
Location: include/linux/cpuhotplug.h:411
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54342)
Location: include/linux/cpuhotplug.h:411
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
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
In block/bio.c (ffffffff8176a93c)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/blk-mq.c (ffffffff8177cf5d)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In io_uring/io-wq.c (ffffffff817e87d4)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff81b2674b)
Location: include/linux/cpuhotplug.h:409
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7892)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/net/virtio_net.c (ffffffff81c4c444)
Location: include/linux/cpuhotplug.h:409
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
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
In block/bio.c (ffffffff817acd9c)
Location: include/linux/cpuhotplug.h:394
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/blk-mq.c (ffffffff817bf2ed)
Location: include/linux/cpuhotplug.h:394
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
```
```
In io_uring/io-wq.c (ffffffff8182e79f)
Location: include/linux/cpuhotplug.h:394
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/iommu/iova.c (ffffffff81b7dadf)
Location: include/linux/cpuhotplug.h:394
Inline: True
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbb71)
Location: include/linux/cpuhotplug.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/net/virtio_net.c (ffffffff81d01af4)
Location: include/linux/cpuhotplug.h:394
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
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
In block/blk-mq.c (ffff8000105f1f40)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In drivers/perf/arm-ccn.c (ffff800010b93a64)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
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
In arch/arm/mach-imx/mmdc.c (c0333384)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In block/blk-mq.c (c079e034)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In drivers/perf/arm-ccn.c (c0c7cbe0)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788fd8)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In block/blk-mq.c (ffffffe0004308c4)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eac8a)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db1da)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6d1a)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ffcbe)
Location: include/linux/cpuhotplug.h:308
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
</ul>

## Differences
