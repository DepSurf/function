# Function: <code>arch_set_max_freq_ratio</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106a425)
Location: arch/x86/kernel/smpboot.c:1837
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8106b720-ffffffff8106b742: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b525)
Location: arch/x86/kernel/smpboot.c:1831
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:amd_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8106b360-ffffffff8106b382: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106cb15)
Location: arch/x86/kernel/smpboot.c:1830
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8106bde0-ffffffff8106be02: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077b12)
Location: arch/x86/kernel/smpboot.c:1837
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81076940-ffffffff81076962: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81061055)
Location: arch/x86/kernel/cpu/aperfmperf.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81060f40-ffffffff81060f6a: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f975)
Location: arch/x86/kernel/cpu/aperfmperf.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8106f7a0-ffffffff8106f7ca: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81071575)
Location: arch/x86/kernel/cpu/aperfmperf.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff810713a0-ffffffff810713ca: arch_set_max_freq_ratio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void arch_set_max_freq_ratio(bool turbo_disabled);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078d35)
Location: arch/x86/kernel/cpu/aperfmperf.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81078b60-ffffffff81078b8a: arch_set_max_freq_ratio (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
