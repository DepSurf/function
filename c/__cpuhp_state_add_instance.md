# Function: <code>__cpuhp_state_add_instance</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089080)
Location: kernel/cpu.c:1417
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/padata.c:padata_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff81089080-ffffffff810891d9: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086ff0)
Location: kernel/cpu.c:1386
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff81086ff0-ffffffff8108707d: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108dd60)
Location: kernel/cpu.c:1574
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8108dd60-ffffffff8108dded: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81091640)
Location: kernel/cpu.c:1656
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81091640-ffffffff8109169d: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81099920)
Location: kernel/cpu.c:1678
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81099920-ffffffff8109997d: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dc90)
Location: kernel/cpu.c:1704
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8109dc90-ffffffff8109dcef: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a41e0)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff810a41e0-ffffffff810a423f: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab450)
Location: kernel/cpu.c:1850
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff810ab450-ffffffff810ab4e4: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6cd0)
Location: kernel/cpu.c:1861
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - fs/io-wq.c:io_wq_create
```
**Symbols:**

```
ffffffff810a6cd0-ffffffff810a6d64: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7d90)
Location: kernel/cpu.c:1964
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - fs/io-wq.c:io_wq_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/iommu/iova.c:init_iova_domain
```
**Symbols:**

```
ffffffff810a7d90-ffffffff810a7e24: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9820)
Location: kernel/cpu.c:1994
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - fs/io-wq.c:io_wq_create
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/iommu/iova.c:init_iova_domain
```
**Symbols:**

```
ffffffff810b9820-ffffffff810b98b4: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810d0250)
Location: kernel/cpu.c:2016
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - io_uring/io-wq.c:io_wq_create
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff810d0250-ffffffff810d0323: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eea80)
Location: kernel/cpu.c:2040
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - io_uring/io-wq.c:io_wq_create
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff810eea80-ffffffff810eeb53: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810faa60)
Location: kernel/cpu.c:2425
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - io_uring/io-wq.c:io_wq_create
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
```
**Symbols:**

```
ffffffff810faa60-ffffffff810fab33: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103e80)
Location: kernel/cpu.c:2471
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - io_uring/io-wq.c:io_wq_create
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
```
**Symbols:**

```
ffffffff81103e80-ffffffff81103f53: __cpuhp_state_add_instance (STB_GLOBAL)
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
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100fa030)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
**Symbols:**

```
ffff8000100fa030-ffff8000100fa10c: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0358268)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
```
**Symbols:**

```
c0358268-c0358314: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001411b0)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c0000000001411b0-c0000000001412e0: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c41e0)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffe0000c41e0-ffffffe0000c421a: __cpuhp_state_add_instance (STB_GLOBAL)
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
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109db00)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8109db00-ffffffff8109db5f: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c520)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8108c520-ffffffff8108c57f: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dab0)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8109dab0-ffffffff8109db0f: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cpuhp_state_add_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5940)
Location: kernel/cpu.c:1719
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/zswap.c:zswap_pool_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff810a5940-ffffffff810a59f7: __cpuhp_state_add_instance (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
