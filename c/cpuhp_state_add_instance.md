# Function: <code>cpuhp_state_add_instance</code>

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
In kernel/trace/ring_buffer.c (ffffffff8115cc6c)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81206b1b)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In net/core/flow.c (ffffffff817cf047)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_init
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
In kernel/trace/ring_buffer.c (ffffffff8115fcbc)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81212666)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In net/core/flow.c (ffffffff817ee3d4)
Location: include/linux/cpuhotplug.h:254
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_init
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
In kernel/trace/ring_buffer.c (ffffffff8116cd8c)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8122cd56)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff8117bd48)
Location: include/linux/cpuhotplug.h:281
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8124f932)
Location: include/linux/cpuhotplug.h:281
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff81188e48)
Location: include/linux/cpuhotplug.h:287
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81263c52)
Location: include/linux/cpuhotplug.h:287
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff81194f6a)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8127ebd9)
Location: include/linux/cpuhotplug.h:292
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811a0a2a)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8128e619)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811b7014)
Location: include/linux/cpuhotplug.h:299
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff812c12c9)
Location: include/linux/cpuhotplug.h:299
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811b4bdd)
Location: include/linux/cpuhotplug.h:304
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff812ccde9)
Location: include/linux/cpuhotplug.h:304
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811b3f9c)
Location: include/linux/cpuhotplug.h:312
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff812d3989)
Location: include/linux/cpuhotplug.h:312
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811ddfac)
Location: include/linux/cpuhotplug.h:385
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8131960b)
Location: include/linux/cpuhotplug.h:385
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff812150f4)
Location: include/linux/cpuhotplug.h:391
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff813848f8)
Location: include/linux/cpuhotplug.h:391
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff8125e7c3)
Location: include/linux/cpuhotplug.h:395
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81402528)
Location: include/linux/cpuhotplug.h:395
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff812759a3)
Location: include/linux/cpuhotplug.h:393
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff814353e1)
Location: include/linux/cpuhotplug.h:393
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1bdc2)
Location: include/linux/cpuhotplug.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
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
In kernel/trace/ring_buffer.c (ffffffff8129021e)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff8146e585)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71922)
Location: include/linux/cpuhotplug.h:378
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
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
In kernel/trace/ring_buffer.c (ffff80001021a22c)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffff80001032b29c)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In drivers/perf/arm_pmu.c (ffff800010b95630)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_register
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b97078)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b978bc)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b980d4)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b9907c)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a568)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9bc20)
Location: include/linux/cpuhotplug.h:293
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
In kernel/trace/ring_buffer.c (c04576c8)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (c054151c)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In drivers/perf/arm_pmu.c (c0c7ebd4)
Location: include/linux/cpuhotplug.h:293
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
In kernel/trace/ring_buffer.c (c00000000029d550)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (c0000000004032dc)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffe000177f08)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffe000229e60)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff8119904a)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81286bf9)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff8118c88a)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81278a59)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff81196e1a)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff81284a09)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
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
In kernel/trace/ring_buffer.c (ffffffff811a4a2a)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In mm/zswap.c (ffffffff812946a9)
Location: include/linux/cpuhotplug.h:293
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
</details>
</li>
</ul>

## Differences
