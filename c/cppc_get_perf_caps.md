# Function: <code>cppc_get_perf_caps</code>

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
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81525e49)
Location: drivers/acpi/cppc_acpi.c:972
Inline: False
```
**Symbols:**

```
ffffffff81525e49-ffffffff81525fbf: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81538a10)
Location: drivers/acpi/cppc_acpi.c:977
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
```
**Symbols:**

```
ffffffff81538a10-ffffffff81538c00: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8159a2b0)
Location: drivers/acpi/cppc_acpi.c:1031
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
```
**Symbols:**

```
ffffffff8159a2b0-ffffffff8159a4c2: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d1bb0)
Location: drivers/acpi/cppc_acpi.c:1060
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
```
**Symbols:**

```
ffffffff815d1bb0-ffffffff815d1f54: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815eb2b0)
Location: drivers/acpi/cppc_acpi.c:1102
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff815eb2b0-ffffffff815eb6ac: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161d050)
Location: drivers/acpi/cppc_acpi.c:1098
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff8161d050-ffffffff8161d464: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163eb00)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff8163eb00-ffffffff8163ef14: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816ec000)
Location: drivers/acpi/cppc_acpi.c:1082
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_acpi_perf_limits
```
**Symbols:**

```
ffffffff816ec000-ffffffff816ec410: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81709660)
Location: drivers/acpi/cppc_acpi.c:1068
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:amd_set_max_freq_ratio
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:get_max_boost_ratio
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81709660-ffffffff81709a7a: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816eac80)
Location: drivers/acpi/cppc_acpi.c:1060
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff816eac80-ffffffff816eb08e: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81764b20)
Location: drivers/acpi/cppc_acpi.c:1082
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81764b20-ffffffff81764fb6: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81898cd0)
Location: drivers/acpi/cppc_acpi.c:1160
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81898cd0-ffffffff81899177: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff819e1040)
Location: drivers/acpi/cppc_acpi.c:1163
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff819e1040-ffffffff819e14e7: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a29000)
Location: drivers/acpi/cppc_acpi.c:1177
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
  - drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81a29000-ffffffff81a294a7: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a741d0)
Location: drivers/acpi/cppc_acpi.c:1180
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:cppc_init_perf
  - drivers/cpufreq/intel_pstate.c:hwp_get_cpu_scaling
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81a741d0-ffffffff81a74677: cppc_get_perf_caps (STB_GLOBAL)
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
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a9c00)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
```
**Symbols:**

```
ffff8000107a9c00-ffff8000107aa014: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
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
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8160a530)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff8160a530-ffffffff8160a944: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815fc170)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff815fc170-ffffffff815fc584: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81632940)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff81632940-ffffffff81632d54: cppc_get_perf_caps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cppc_get_perf_caps(int cpunum, struct cppc_perf_caps *perf_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164cc70)
Location: drivers/acpi/cppc_acpi.c:1100
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_nominal_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_freq
  - drivers/acpi/cppc_acpi.c:show_lowest_nonlinear_perf
  - drivers/acpi/cppc_acpi.c:show_nominal_perf
  - drivers/acpi/cppc_acpi.c:show_lowest_perf
  - drivers/acpi/cppc_acpi.c:show_highest_perf
  - drivers/cpufreq/intel_pstate.c:show_base_frequency
```
**Symbols:**

```
ffffffff8164cc70-ffffffff8164d084: cppc_get_perf_caps (STB_GLOBAL)
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
