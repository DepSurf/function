# Function: <code>cpuhp_setup_state_multi</code>

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
In kernel/trace/trace.c (ffffffff81fe97a5)
Location: include/linux/cpuhotplug.h:205
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
```
```
In kernel/padata.c (ffffffff81fec3ac)
Location: include/linux/cpuhotplug.h:205
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff81ff1e5b)
Location: include/linux/cpuhotplug.h:205
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff820031a2)
Location: include/linux/cpuhotplug.h:205
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In net/core/flow.c (ffffffff820278a4)
Location: include/linux/cpuhotplug.h:205
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_hp_init
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
In kernel/trace/trace.c (ffffffff820ca186)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff820cd3be)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff820d443d)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff820e6a70)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In net/core/flow.c (ffffffff8210add1)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_hp_init
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
In kernel/trace/trace.c (ffffffff826d2855)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff826d5deb)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff826dd003)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff826ef7f1)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff826fd066)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff82700081)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff82707532)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff82719c5b)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828b3f80)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff828b70eb)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828be904)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828d1c54)
Location: include/linux/cpuhotplug.h:260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828ccaed)
Location: include/linux/cpuhotplug.h:265
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828d06c4)
Location: include/linux/cpuhotplug.h:265
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828d7ac3)
Location: include/linux/cpuhotplug.h:265
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828ebc4f)
Location: include/linux/cpuhotplug.h:265
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828d502c)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828d8b01)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828dff34)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828f481e)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff82cf599b)
Location: include/linux/cpuhotplug.h:272
Inline: True
```
```
In kernel/padata.c (ffffffff82cf807d)
Location: include/linux/cpuhotplug.h:272
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff82cfd665)
Location: include/linux/cpuhotplug.h:272
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff82d08bee)
Location: include/linux/cpuhotplug.h:272
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff82fe2580)
Location: include/linux/cpuhotplug.h:277
Inline: True
```
```
In kernel/padata.c (ffffffff82fe4d76)
Location: include/linux/cpuhotplug.h:277
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff82fea096)
Location: include/linux/cpuhotplug.h:277
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In fs/io-wq.c (ffffffff82fee709)
Location: include/linux/cpuhotplug.h:277
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_init
```
```
In block/blk-mq.c (ffffffff82ff61ab)
Location: include/linux/cpuhotplug.h:277
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff831eca51)
Location: include/linux/cpuhotplug.h:285
Inline: True
```
```
In kernel/padata.c (ffffffff831ef4a2)
Location: include/linux/cpuhotplug.h:285
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff831f48bc)
Location: include/linux/cpuhotplug.h:285
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In fs/io-wq.c (ffffffff831f8fc8)
Location: include/linux/cpuhotplug.h:285
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_init
```
```
In block/blk-mq.c (ffffffff83200e7d)
Location: include/linux/cpuhotplug.h:285
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In drivers/iommu/iova.c (ffffffff817a3091)
Location: include/linux/cpuhotplug.h:285
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
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
In kernel/trace/trace.c (ffffffff832d158a)
Location: include/linux/cpuhotplug.h:357
Inline: True
```
```
In kernel/padata.c (ffffffff832d4bd3)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff832dab82)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In fs/io-wq.c (ffffffff832dfea9)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_init
```
```
In block/bio.c (ffffffff832e8381)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-mq.c (ffffffff832e8553)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In drivers/iommu/iova.c (ffffffff8182c461)
Location: include/linux/cpuhotplug.h:357
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
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
In kernel/trace/trace.c (ffffffff834857ae)
Location: include/linux/cpuhotplug.h:363
Inline: True
```
```
In kernel/padata.c (ffffffff83489283)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff8348fd00)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/bio.c (ffffffff8349f94f)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-mq.c (ffffffff8349fb78)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In io_uring/io-wq.c (ffffffff834a02df)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_init
```
```
In drivers/iommu/iova.c (ffffffff8196d7c0)
Location: include/linux/cpuhotplug.h:363
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d9293)
Location: include/linux/cpuhotplug.h:363
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
In kernel/trace/trace.c (ffffffff83eb47aa)
Location: include/linux/cpuhotplug.h:367
Inline: True
```
```
In kernel/padata.c (ffffffff83eb98e5)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff83ec255d)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/bio.c (ffffffff83ed845f)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-mq.c (ffffffff83ed86e5)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In io_uring/io-wq.c (ffffffff83ed90d5)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_init
```
```
In drivers/iommu/iova.c (ffffffff81ad8080)
Location: include/linux/cpuhotplug.h:367
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54303)
Location: include/linux/cpuhotplug.h:367
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
In kernel/trace/trace.c (ffffffff836d9aba)
Location: include/linux/cpuhotplug.h:365
Inline: True
```
```
In kernel/padata.c (ffffffff836def25)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff814357a6)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - mm/zswap.c:zswap_setup
```
```
In block/bio.c (ffffffff836fd78f)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-mq.c (ffffffff836fda15)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In io_uring/io-wq.c (ffffffff836feb45)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_init
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1bd84)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
```
```
In drivers/iommu/iova.c (ffffffff81b25fc0)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7853)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/net/virtio_net.c (ffffffff83720ca5)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
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
In kernel/trace/trace.c (ffffffff8390c06a)
Location: include/linux/cpuhotplug.h:350
Inline: True
```
```
In kernel/padata.c (ffffffff83911565)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In mm/zswap.c (ffffffff8146e9d7)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - mm/zswap.c:zswap_setup
```
```
In block/bio.c (ffffffff83930def)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - block/bio.c:init_bio
```
```
In block/blk-mq.c (ffffffff839310d4)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
```
```
In io_uring/io-wq.c (ffffffff839323a5)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_init
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b718e4)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
```
```
In drivers/iommu/iova.c (ffffffff81b7cdf0)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbb32)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/net/virtio_net.c (ffffffff83954ba5)
Location: include/linux/cpuhotplug.h:350
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
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
In kernel/trace/trace.c (ffff80001144d8ac)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffff800011451618)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffff800011459154)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffff80001146ec74)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In drivers/perf/arm-ccn.c (ffff8000114ad8d0)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_init
```
```
In drivers/perf/arm_pmu.c (ffff800010b94524)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:arm_pmu_hp_init
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff8000114ad96c)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff8000114ad9fc)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff8000114ada8c)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init
```
```
In drivers/perf/qcom_l2_pmu.c (ffff8000114adb18)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:register_l2_cache_pmu_driver
```
```
In drivers/perf/qcom_l3_pmu.c (ffff8000114adb70)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:register_qcom_l3_cache_pmu_driver
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b994)
Location: include/linux/cpuhotplug.h:266
Inline: True
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
In arch/arm/mach-imx/mmdc.c (c0333274)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In kernel/trace/trace.c (c1527e40)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (c152c0f4)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (c1533090)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (c1547af0)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In drivers/perf/arm-ccn.c (c15b1a14)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_init
```
```
In drivers/perf/arm_pmu.c (c0c7dc78)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:arm_pmu_hp_init
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
In kernel/trace/trace.c (c000000001373e94)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (c000000001379138)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (c000000001382b64)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (c00000000139eb48)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffe00000deaa)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In mm/zswap.c (ffffffe0000176e0)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffe00002923c)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828bdedd)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828c19b2)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828c8de8)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828dd6d2)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828b657d)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828ba052)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828c150d)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828d5dee)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828d0c60)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828d4735)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828dbb68)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828f0446)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
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
In kernel/trace/trace.c (ffffffff828d6081)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff828d9b56)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
```
```
In mm/zswap.c (ffffffff828e0f89)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In block/blk-mq.c (ffffffff828f5868)
Location: include/linux/cpuhotplug.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
</details>
</li>
</ul>

## Differences
