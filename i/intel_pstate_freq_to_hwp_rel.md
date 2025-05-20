# Function: <code>intel_pstate_freq_to_hwp_rel</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_freq_to_hwp_rel(struct cpudata *cpu, int freq, unsigned int relation);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e63019)
Location: drivers/cpufreq/intel_pstate.c:532
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hybrid_hwp_adjust
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81e5fd00-ffffffff81e5fd9f: intel_pstate_freq_to_hwp_rel (STB_LOCAL)
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
</ul>
