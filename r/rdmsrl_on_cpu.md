# Function: <code>rdmsrl_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b480)
Location: arch/x86/lib/msr-smp.c:50
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
**Symbols:**

```
ffffffff8141b480-ffffffff8141b4fa: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463640)
Location: arch/x86/lib/msr-smp.c:50
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
```
**Symbols:**

```
ffffffff81463640-ffffffff814636ba: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814828e0)
Location: arch/x86/lib/msr-smp.c:50
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff814828e0-ffffffff8148295a: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c0d0)
Location: arch/x86/lib/msr-smp.c:50
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8148c0d0-ffffffff8148c149: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c81c0)
Location: arch/x86/lib/msr-smp.c:51
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff814c81c0-ffffffff814c8239: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f90d0)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff814f90d0-ffffffff814f9149: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150d970)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8150d970-ffffffff8150d9e9: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c020)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8153c020-ffffffff8153c09a: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155ce30)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8155ce30-ffffffff8155ceaa: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6850)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff815e6850-ffffffff815e68c9: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160b9a0)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8160b9a0-ffffffff8160ba19: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eec80)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff815eec80-ffffffff815eecf9: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165bd90)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8165bd90-ffffffff8165be09: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774bb0)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff81774bb0-ffffffff81774c34: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5690)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff818a5690-ffffffff818a5714: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e84b0)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff818e84b0-ffffffff818e8534: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192f950)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical
  - drivers/cpufreq/intel_pstate.c:core_get_min_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_cap
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8192f950-ffffffff8192f9d4: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555420)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff81555420-ffffffff8155549a: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81545650)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff81545650-ffffffff815456ca: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81551160)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff81551160-ffffffff815511da: rdmsrl_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdmsrl_on_cpu(unsigned int cpu, u32 msr_no, u64 *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156afa0)
Location: arch/x86/lib/msr-smp.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_show
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_hwp_max
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
**Symbols:**

```
ffffffff8156afa0-ffffffff8156b01a: rdmsrl_on_cpu (STB_GLOBAL)
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
