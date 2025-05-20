# Function: <code>__cpuhp_remove_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084150)
Location: kernel/cpu.c:1546
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
**Symbols:**

```
ffffffff81084150-ffffffff81084219: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810894b0)
Location: kernel/cpu.c:1581
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:trace_init
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
**Symbols:**

```
ffffffff810894b0-ffffffff810895b5: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810866b0)
Location: kernel/cpu.c:1576
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
**Symbols:**

```
ffffffff810866b0-ffffffff8108671f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d310)
Location: kernel/cpu.c:1764
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
```
**Symbols:**

```
ffffffff8108d310-ffffffff8108d37f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090c80)
Location: kernel/cpu.c:1846
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81090c80-ffffffff81090ccf: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098d40)
Location: kernel/cpu.c:1868
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81098d40-ffffffff81098d8f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d2c0)
Location: kernel/cpu.c:1894
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff8109d2c0-ffffffff8109d30f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3810)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff810a3810-ffffffff810a385f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa8b0)
Location: kernel/cpu.c:2040
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810aa8b0-ffffffff810aa92f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6140)
Location: kernel/cpu.c:2051
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810a6140-ffffffff810a61bf: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6f90)
Location: kernel/cpu.c:2154
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff810a6f90-ffffffff810a700f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8930)
Location: kernel/cpu.c:2185
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff810b8930-ffffffff810b89af: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cf1f0)
Location: kernel/cpu.c:2207
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff810cf1f0-ffffffff810cf2b1: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ed660)
Location: kernel/cpu.c:2231
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff810ed660-ffffffff810ed721: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f91f0)
Location: kernel/cpu.c:2616
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zswap.c:zswap_setup
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff810f91f0-ffffffff810f92b1: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102600)
Location: kernel/cpu.c:2662
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/mshyperv.c:hv_machine_shutdown
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_exit
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81102600-ffffffff811026c1: __cpuhp_remove_state (STB_GLOBAL)
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9030)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/firmware/arm_sdei.c:sdei_reboot_notifier
  - drivers/firmware/arm_sdei.c:sdei_device_freeze
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - drivers/perf/arm-ccn.c:arm_ccn_init
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_exit
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init
```
**Symbols:**

```
ffff8000100f9030-ffff8000100f90ec: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035725c)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_exit
  - drivers/perf/arm-ccn.c:arm_ccn_init
```
**Symbols:**

```
c035725c-c03572f4: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013fc80)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
c00000000013fc80-c00000000013fd94: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3c24)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
```
**Symbols:**

```
ffffffe0000c3c24-ffffffe0000c3c56: __cpuhp_remove_state (STB_GLOBAL)
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
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d130)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff8109d130-ffffffff8109d17f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bb60)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/vmbus_drv.c:hv_kexec_handler
```
**Symbols:**

```
ffffffff8108bb60-ffffffff8108bbaf: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d0e0)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff8109d0e0-ffffffff8109d12f: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cpuhp_remove_state(enum cpuhp_state state, bool invoke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4f10)
Location: kernel/cpu.c:1909
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_exit
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_exit
  - kernel/padata.c:padata_driver_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_exit
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff810a4f10-ffffffff810a4fa8: __cpuhp_remove_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
