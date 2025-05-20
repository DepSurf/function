# Function: <code>perf_pmu_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117e510)
Location: kernel/events/core.c:7624
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8117e510-ffffffff8117e807: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ea90)
Location: kernel/events/core.c:8640
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8118ea90-ffffffff8118ee50: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119d3f0)
Location: kernel/events/core.c:8829
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8119d3f0-ffffffff8119d7b2: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a40d0)
Location: kernel/events/core.c:9040
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811a40d0-ffffffff811a448b: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b8d30)
Location: kernel/events/core.c:9056
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811b8d30-ffffffff811b9124: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d8480)
Location: kernel/events/core.c:9578
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811d8480-ffffffff811d884f: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e85c0)
Location: kernel/events/core.c:9621
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811e85c0-ffffffff811e89ae: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff880)
Location: kernel/events/core.c:9930
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811ff880-ffffffff811ffc85: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c9e0)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8120c9e0-ffffffff8120cde5: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81235360)
Location: kernel/events/core.c:10594
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff81235360-ffffffff812357bd: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123de10)
Location: kernel/events/core.c:10876
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8123de10-ffffffff8123e26d: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241050)
Location: kernel/events/core.c:11006
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff81241050-ffffffff812414ad: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127ba70)
Location: kernel/events/core.c:11118
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff8127ba70-ffffffff8127befd: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cf7d0)
Location: kernel/events/core.c:11054
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff812cf7d0-ffffffff812cfc6c: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81339440)
Location: kernel/events/core.c:11394
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff81339440-ffffffff813397cb: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:11437
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff820e155c-ffffffff820e1570: perf_pmu_register.cold (STB_LOCAL)
ffffffff81368f40-ffffffff813692a9: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:11521
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/iommu.c:init_one_iommu
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff821bdf6b-ffffffff821bdf7f: perf_pmu_register.cold (STB_LOCAL)
ffffffff813922a0-ffffffff81392609: perf_pmu_register (STB_GLOBAL)
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
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102934d8)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_tp_register
  - kernel/events/core.c:perf_tp_register
  - kernel/events/core.c:perf_tp_register
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_add
```
**Symbols:**

```
ffff8000102934d8-ffff8000102938b4: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c40e8)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm_pmu.c:armpmu_register
```
**Symbols:**

```
c04c40e8-c04c4518: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003462f0)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/powerpc/perf/core-book3s.c:register_power_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/hv-24x7.c:hv_24x7_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
c0000000003462f0-c000000000346868: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c72ae)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/riscv/kernel/perf_event.c:init_hw_perf_events
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffe0001c72ae-ffffffe0001c7626: perf_pmu_register (STB_GLOBAL)
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
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205000)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff81205000-ffffffff81205405: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f7d90)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff811f7d90-ffffffff811f8195: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202dd0)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff81202dd0-ffffffff812031d5: perf_pmu_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu *pmu, const char *name, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812129a0)
Location: kernel/events/core.c:10046
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - arch/x86/events/msr.c:msr_init
  - arch/x86/events/intel/bts.c:bts_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_pmu_register
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
```
**Symbols:**

```
ffffffff812129a0-ffffffff81212da5: perf_pmu_register (STB_GLOBAL)
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
