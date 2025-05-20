# Function: <code>cpufreq_cpu_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816aeac0)
Location: drivers/cpufreq/cpufreq.c:276
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stat_notifier_trans
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff816aeac0-ffffffff816aeb59: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710320)
Location: drivers/cpufreq/cpufreq.c:230
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81710320-ffffffff817103b9: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742340)
Location: drivers/cpufreq/cpufreq.c:230
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81742340-ffffffff817423dc: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817609e0)
Location: drivers/cpufreq/cpufreq.c:230
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff817609e0-ffffffff81760a7d: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d69b0)
Location: drivers/cpufreq/cpufreq.c:236
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff817d69b0-ffffffff817d6a4d: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f640)
Location: drivers/cpufreq/cpufreq.c:220
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8181f640-ffffffff8181f6ca: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b4e0)
Location: drivers/cpufreq/cpufreq.c:220
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8184b4e0-ffffffff8184b569: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:210
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff81892382-ffffffff81892398: cpufreq_cpu_get.cold (STB_LOCAL)
ffffffff8188e580-ffffffff8188e5ef: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0710)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818c0710-ffffffff818c078b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819942d0)
Location: drivers/cpufreq/cpufreq.c:218
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff819942d0-ffffffff8199434b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996f90)
Location: drivers/cpufreq/cpufreq.c:218
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81996f90-ffffffff8199700b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197bc40)
Location: drivers/cpufreq/cpufreq.c:215
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
```
**Symbols:**

```
ffffffff8197bc40-ffffffff8197bcbb: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a24eb0)
Location: drivers/cpufreq/cpufreq.c:215
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_online
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
```
**Symbols:**

```
ffffffff81a24eb0-ffffffff81a24f2b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ca20)
Location: drivers/cpufreq/cpufreq.c:216
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81b8ca20-ffffffff81b8caa1: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c4d0)
Location: drivers/cpufreq/cpufreq.c:216
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d2c4d0-ffffffff81d2c551: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d95760)
Location: drivers/cpufreq/cpufreq.c:221
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d95760-ffffffff81d957e7: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d250)
Location: drivers/cpufreq/cpufreq.c:222
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81e4d250-ffffffff81e4d2d7: cpufreq_cpu_get (STB_GLOBAL)
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
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1ff80)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
ffff800010b1ff80-ffff800010b200c8: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf7ee8)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
c0bf7ee8-c0bf7fd0: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0fc60)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
**Symbols:**

```
c000000000c0fc60-c000000000c0fd70: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
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
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864e30)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81864e30-ffffffff81864eab: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182dae0)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8182dae0-ffffffff8182db5b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b5bc0)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818b5bc0-ffffffff818b5c3b: cpufreq_cpu_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpufreq_policy *cpufreq_cpu_get(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1e70)
Location: drivers/cpufreq/cpufreq.c:213
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818d1e70-ffffffff818d1eeb: cpufreq_cpu_get (STB_GLOBAL)
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
