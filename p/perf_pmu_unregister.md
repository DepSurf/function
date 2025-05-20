# Function: <code>perf_pmu_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811794c0)
Location: kernel/events/core.c:7726
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff811794c0-ffffffff811795e4: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81189d30)
Location: kernel/events/core.c:8757
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff81189d30-ffffffff81189e72: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81199110)
Location: kernel/events/core.c:8946
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff81199110-ffffffff8119926a: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1e70)
Location: kernel/events/core.c:9156
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811a1e70-ffffffff811a1f3e: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5af0)
Location: kernel/events/core.c:9172
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811b5af0-ffffffff811b5bca: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d51d0)
Location: kernel/events/core.c:9694
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811d51d0-ffffffff811d52b1: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e40d0)
Location: kernel/events/core.c:9740
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811e40d0-ffffffff811e4193: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb2b0)
Location: kernel/events/core.c:10049
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811fb2b0-ffffffff811fb365: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208380)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff81208380-ffffffff81208435: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230ef0)
Location: kernel/events/core.c:10730
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
**Symbols:**

```
ffffffff81230ef0-ffffffff81230fa6: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ab00)
Location: kernel/events/core.c:11012
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
**Symbols:**

```
ffffffff8123ab00-ffffffff8123abb6: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f2d0)
Location: kernel/events/core.c:11142
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
**Symbols:**

```
ffffffff8123f2d0-ffffffff8123f386: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279e40)
Location: kernel/events/core.c:11254
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
**Symbols:**

```
ffffffff81279e40-ffffffff81279ef6: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd220)
Location: kernel/events/core.c:11190
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
```
**Symbols:**

```
ffffffff812cd220-ffffffff812cd2e9: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813352c0)
Location: kernel/events/core.c:11502
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
```
**Symbols:**

```
ffffffff813352c0-ffffffff81335380: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366000)
Location: kernel/events/core.c:11537
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
```
**Symbols:**

```
ffffffff81366000-ffffffff813660c7: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f120)
Location: kernel/events/core.c:11621
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
```
**Symbols:**

```
ffffffff8138f120-ffffffff8138f1e7: perf_pmu_unregister (STB_GLOBAL)
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
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291c10)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_remove
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_remove
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_remove
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_remove
  - drivers/perf/xgene_pmu.c:xgene_pmu_remove
  - drivers/perf/xgene_pmu.c:xgene_pmu_remove
  - drivers/perf/xgene_pmu.c:xgene_pmu_remove
  - drivers/perf/xgene_pmu.c:xgene_pmu_remove
```
**Symbols:**

```
ffff800010291c10-ffff800010291cdc: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c2bb8)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_remove
  - drivers/perf/arm-ccn.c:arm_ccn_remove
```
**Symbols:**

```
c04c2bb8-c04c2c7c: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000340080)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:unregister_thread_imc
```
**Symbols:**

```
c000000000340080-c0000000003401b4: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4452)
Location: kernel/events/core.c:10165
Inline: False
```
**Symbols:**

```
ffffffe0001c4452-ffffffe0001c4518: perf_pmu_unregister (STB_GLOBAL)
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
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812009a0)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff812009a0-ffffffff81200a55: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f36f0)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811f36f0-ffffffff811f37a5: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe770)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff811fe770-ffffffff811fe825: perf_pmu_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_pmu_unregister(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d7d0)
Location: kernel/events/core.c:10165
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
```
**Symbols:**

```
ffffffff8120d7d0-ffffffff8120d885: perf_pmu_unregister (STB_GLOBAL)
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
