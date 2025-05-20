# Function: <code>perf_pmu_migrate_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117dec0)
Location: kernel/events/core.c:8660
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_change_context
```
**Symbols:**

```
ffffffff8117dec0-ffffffff8117e146: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81190010)
Location: kernel/events/core.c:9844
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff81190010-ffffffff811902c6: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0020)
Location: kernel/events/core.c:10104
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811a0020-ffffffff811a02cf: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7c20)
Location: kernel/events/core.c:10351
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811a7c20-ffffffff811a7e94: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb390)
Location: kernel/events/core.c:10383
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811bb390-ffffffff811bb604: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db2b0)
Location: kernel/events/core.c:10913
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811db2b0-ffffffff811db522: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb5f0)
Location: kernel/events/core.c:10956
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811eb5f0-ffffffff811eb862: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202f80)
Location: kernel/events/core.c:11307
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff81202f80-ffffffff81203204: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212310)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff81212310-ffffffff81212594: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c1b0)
Location: kernel/events/core.c:12023
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/intel/uncore.c:uncore_change_context
```
**Symbols:**

```
ffffffff8123c1b0-ffffffff8123c542: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246450)
Location: kernel/events/core.c:12307
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/intel/uncore.c:uncore_change_context
```
**Symbols:**

```
ffffffff81246450-ffffffff812467e2: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124cd00)
Location: kernel/events/core.c:12497
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/intel/uncore.c:uncore_change_context
```
**Symbols:**

```
ffffffff8124cd00-ffffffff8124d043: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81289500)
Location: kernel/events/core.c:12618
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
```
**Symbols:**

```
ffffffff81289500-ffffffff81289913: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dcd40)
Location: kernel/events/core.c:12588
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
**Symbols:**

```
ffffffff812dcd40-ffffffff812dd16b: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81345540)
Location: kernel/events/core.c:12869
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
**Symbols:**

```
ffffffff81345540-ffffffff813457c5: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813765e0)
Location: kernel/events/core.c:12909
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
**Symbols:**

```
ffffffff813765e0-ffffffff81376875: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139f8e0)
Location: kernel/events/core.c:13001
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
**Symbols:**

```
ffffffff8139f8e0-ffffffff8139fb06: perf_pmu_migrate_context (STB_GLOBAL)
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
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029c7b8)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
**Symbols:**

```
ffff80001029c7b8-ffff80001029ca68: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cbd80)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu
```
**Symbols:**

```
c04cbd80-c04cc000: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034cd80)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
**Symbols:**

```
c00000000034cd80-c00000000034d144: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cb110)
Location: kernel/events/core.c:11420
Inline: False
```
**Symbols:**

```
ffffffe0001cb110-ffffffe0001cb354: perf_pmu_migrate_context (STB_GLOBAL)
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
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a960)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff8120a960-ffffffff8120abe4: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd740)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff811fd740-ffffffff811fd9c4: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208700)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff81208700-ffffffff81208984: perf_pmu_migrate_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu *pmu, int src_cpu, int dst_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81217490)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
**Symbols:**

```
ffffffff81217490-ffffffff81217714: perf_pmu_migrate_context (STB_GLOBAL)
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
