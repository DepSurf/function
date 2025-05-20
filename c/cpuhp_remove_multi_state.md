# Function: <code>cpuhp_remove_multi_state</code>

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
In kernel/trace/trace.c (ffffffff81fe98b1)
Location: include/linux/cpuhotplug.h:283
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
```
```
In kernel/padata.c (ffffffff821ccea8)
Location: include/linux/cpuhotplug.h:283
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff820ca3ae)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff822c1fb0)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff826d2a7d)
Location: include/linux/cpuhotplug.h:348
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff828d5130)
Location: include/linux/cpuhotplug.h:348
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff826fd278)
Location: include/linux/cpuhotplug.h:347
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff82906986)
Location: include/linux/cpuhotplug.h:347
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff828b4192)
Location: include/linux/cpuhotplug.h:353
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/padata.c (ffffffff82ade748)
Location: include/linux/cpuhotplug.h:353
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff828ccd3e)
Location: include/linux/cpuhotplug.h:358
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82b0386b)
Location: include/linux/cpuhotplug.h:358
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
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
In kernel/trace/trace.c (ffffffff828d526d)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82b1275b)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
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
In kernel/trace/trace.c (ffffffff82cf5be0)
Location: include/linux/cpuhotplug.h:365
Inline: True
```
```
In kernel/padata.c (ffffffff82cf8105)
Location: include/linux/cpuhotplug.h:365
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
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
In kernel/trace/trace.c (ffffffff82fe27be)
Location: include/linux/cpuhotplug.h:370
Inline: True
```
```
In kernel/padata.c (ffffffff82fe4dfe)
Location: include/linux/cpuhotplug.h:370
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
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
In kernel/trace/trace.c (ffffffff831eccbe)
Location: include/linux/cpuhotplug.h:378
Inline: True
```
```
In kernel/padata.c (ffffffff831ef52a)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/iova.c (ffffffff817a3188)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_put
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
In kernel/trace/trace.c (ffffffff832d183c)
Location: include/linux/cpuhotplug.h:471
Inline: True
```
```
In kernel/padata.c (ffffffff832d4c5b)
Location: include/linux/cpuhotplug.h:471
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/iova.c (ffffffff8182c558)
Location: include/linux/cpuhotplug.h:471
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_put
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
In kernel/trace/trace.c (ffffffff83485a6f)
Location: include/linux/cpuhotplug.h:477
Inline: True
```
```
In kernel/padata.c (ffffffff8348930b)
Location: include/linux/cpuhotplug.h:477
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/iova.c (ffffffff8196d860)
Location: include/linux/cpuhotplug.h:477
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d9423)
Location: include/linux/cpuhotplug.h:477
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
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
In kernel/trace/trace.c (ffffffff83eb49ef)
Location: include/linux/cpuhotplug.h:481
Inline: True
```
```
In kernel/padata.c (ffffffff83eb99d0)
Location: include/linux/cpuhotplug.h:481
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/iova.c (ffffffff81ad8138)
Location: include/linux/cpuhotplug.h:481
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54492)
Location: include/linux/cpuhotplug.h:481
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
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
In kernel/trace/trace.c (ffffffff836d9b66)
Location: include/linux/cpuhotplug.h:479
Inline: True
```
```
In kernel/padata.c (ffffffff836df010)
Location: include/linux/cpuhotplug.h:479
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1bf1e)
Location: include/linux/cpuhotplug.h:479
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
```
```
In drivers/iommu/iova.c (ffffffff81b26078)
Location: include/linux/cpuhotplug.h:479
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba79e2)
Location: include/linux/cpuhotplug.h:479
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
```
In drivers/net/virtio_net.c (ffffffff83af4a80)
Location: include/linux/cpuhotplug.h:479
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_exit
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
In kernel/trace/trace.c (ffffffff8390c0dd)
Location: include/linux/cpuhotplug.h:464
Inline: True
```
```
In kernel/padata.c (ffffffff83911650)
Location: include/linux/cpuhotplug.h:464
Inline: True
Inline callers:
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71a7e)
Location: include/linux/cpuhotplug.h:464
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
```
```
In drivers/iommu/iova.c (ffffffff81b7cea8)
Location: include/linux/cpuhotplug.h:464
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_cache_get
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbd4e)
Location: include/linux/cpuhotplug.h:464
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
```
In drivers/net/virtio_net.c (ffffffff83d50880)
Location: include/linux/cpuhotplug.h:464
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_exit
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
In kernel/trace/trace.c (ffff80001144da98)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffff8000114b85f0)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
```
```
In drivers/perf/arm-ccn.c (ffff8000114bb4a0)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - drivers/perf/arm-ccn.c:arm_ccn_init
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff8000114bb4cc)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff8000114bb4f8)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff8000114bb524)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init
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
In kernel/trace/trace.c (c152805c)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (c15be8a8)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
```
```
In drivers/perf/arm-ccn.c (c15c17e8)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - drivers/perf/arm-ccn.c:arm_ccn_init
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
In kernel/trace/trace.c (c000000001374104)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (c0000000013cb614)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
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
In kernel/trace/trace.c (ffffffe00000e110)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
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
In kernel/trace/trace.c (ffffffff828be11e)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82af297b)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
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
In kernel/trace/trace.c (ffffffff828b67be)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82ac2da3)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
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
In kernel/trace/trace.c (ffffffff828d0ea1)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82b0da43)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
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
In kernel/trace/trace.c (ffffffff828d62c2)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
```
In kernel/padata.c (ffffffff82b02593)
Location: include/linux/cpuhotplug.h:359
Inline: True
Inline callers:
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
```
</details>
</li>
</ul>

## Differences
