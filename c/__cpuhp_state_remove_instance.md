# Function: <code>__cpuhp_state_remove_instance</code>

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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089370)
Location: kernel/cpu.c:1536
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - net/core/flow.c:flow_cache_fini
```
**Symbols:**

```
ffffffff81089370-ffffffff810894a2: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086080)
Location: kernel/cpu.c:1490
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - net/core/flow.c:flow_cache_fini
```
**Symbols:**

```
ffffffff81086080-ffffffff810861fa: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108cd00)
Location: kernel/cpu.c:1678
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff8108cd00-ffffffff8108ce6c: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810906b0)
Location: kernel/cpu.c:1760
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff810906b0-ffffffff810907d2: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098770)
Location: kernel/cpu.c:1782
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81098770-ffffffff81098892: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cd30)
Location: kernel/cpu.c:1808
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff8109cd30-ffffffff8109ce4f: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3280)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff810a3280-ffffffff810a339f: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa2c0)
Location: kernel/cpu.c:1954
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:__padata_free
  - kernel/padata.c:__padata_free
  - mm/zswap.c:zswap_pool_destroy
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff810aa2c0-ffffffff810aa40c: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5b50)
Location: kernel/cpu.c:1965
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff810a5b50-ffffffff810a5c9c: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6990)
Location: kernel/cpu.c:2068
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff810a6990-ffffffff810a6adc: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2099
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff81ca3e4a-ffffffff81ca3e5f: __cpuhp_state_remove_instance.cold (STB_LOCAL)
ffffffff810b8290-ffffffff810b8416: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2121
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
**Symbols:**

```
ffffffff81e536b9-ffffffff81e536ce: __cpuhp_state_remove_instance.cold (STB_LOCAL)
ffffffff810ceae0-ffffffff810ceca4: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2145
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
```
**Symbols:**

```
ffffffff82055bc4-ffffffff82055bd9: __cpuhp_state_remove_instance.cold (STB_LOCAL)
ffffffff810eced0-ffffffff810ed0b5: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2530
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
```
**Symbols:**

```
ffffffff820d41aa-ffffffff820d41bf: __cpuhp_state_remove_instance.cold (STB_LOCAL)
ffffffff810f89f0-ffffffff810f8bd5: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2576
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_pool_destroy
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_exit_hctx
  - io_uring/io-wq.c:io_wq_put_and_exit
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_cpu_notif_add
```
**Symbols:**

```
ffffffff821af07e-ffffffff821af093: __cpuhp_state_remove_instance.cold (STB_LOCAL)
ffffffff81101e00-ffffffff81101fe5: __cpuhp_state_remove_instance (STB_GLOBAL)
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f8970)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_remove
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_remove
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_remove
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_remove
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
  - drivers/perf/xgene_pmu.c:xgene_pmu_remove
```
**Symbols:**

```
ffff8000100f8970-ffff8000100f8b0c: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0356be8)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_remove
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
```
**Symbols:**

```
c0356be8-c0356d68: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013f3c0)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
c00000000013f3c0-c00000000013f628: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c377c)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffe0000c377c-ffffffe0000c389e: __cpuhp_state_remove_instance (STB_GLOBAL)
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cba0)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff8109cba0-ffffffff8109ccbf: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108b5d0)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff8108b5d0-ffffffff8108b6ef: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cb50)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff8109cb50-ffffffff8109cc6f: __cpuhp_state_remove_instance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node *node, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a48e0)
Location: kernel/cpu.c:1823
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:__zswap_pool_release
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
**Symbols:**

```
ffffffff810a48e0-ffffffff810a4a4f: __cpuhp_state_remove_instance (STB_GLOBAL)
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
