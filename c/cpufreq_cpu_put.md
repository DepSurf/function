# Function: <code>cpufreq_cpu_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816aeb60)
Location: drivers/cpufreq/cpufreq.c:308
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
Direct callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stat_notifier_trans
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_free_table
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff816aeb60-ffffffff816aeb77: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8171359e)
Location: drivers/cpufreq/cpufreq.c:262
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff817103c0-ffffffff817103d7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817453aa)
Location: drivers/cpufreq/cpufreq.c:262
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff817423e0-ffffffff817423f7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763ada)
Location: drivers/cpufreq/cpufreq.c:262
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff81760a80-ffffffff81760a97: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9aca)
Location: drivers/cpufreq/cpufreq.c:268
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff817d6a50-ffffffff817d6a67: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818225b0)
Location: drivers/cpufreq/cpufreq.c:252
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8181f6d0-ffffffff8181f6e7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184e490)
Location: drivers/cpufreq/cpufreq.c:252
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
```
**Symbols:**

```
ffffffff8184b570-ffffffff8184b587: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188ee61)
Location: drivers/cpufreq/cpufreq.c:238
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
```
**Symbols:**

```
ffffffff8188e5f0-ffffffff8188e607: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0c31)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818c0790-ffffffff818c07a7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995d53)
Location: drivers/cpufreq/cpufreq.c:246
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81992610-ffffffff81992627: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998bf7)
Location: drivers/cpufreq/cpufreq.c:246
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81995820-ffffffff81995837: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d677)
Location: drivers/cpufreq/cpufreq.c:243
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8197a690-ffffffff8197a6a7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a26704)
Location: drivers/cpufreq/cpufreq.c:243
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - kernel/sched/topology.c:build_perf_domains
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81a236b0-ffffffff81a236c7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b903b2)
Location: drivers/cpufreq/cpufreq.c:244
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81b8cab0-ffffffff81b8cacd: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d30517)
Location: drivers/cpufreq/cpufreq.c:244
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d2c570-ffffffff81d2c58d: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d99806)
Location: drivers/cpufreq/cpufreq.c:249
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81d95800-ffffffff81d9581d: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e51476)
Location: drivers/cpufreq/cpufreq.c:250
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_get_hw_max_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
Direct callers:
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_cur_state
  - drivers/acpi/processor_thermal.c:processor_get_max_state
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
```
**Symbols:**

```
ffffffff81e4d2f0-ffffffff81e4d30d: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b20150)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
```
**Symbols:**

```
ffff800010b1d168-ffff800010b1d194: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf84d0)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
```
**Symbols:**

```
c0bf7fd0-c0bf7ff0: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c10530)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
```
**Symbols:**

```
c000000000c0fd70-c000000000c0fda8: cpufreq_cpu_put (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865351)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81864eb0-ffffffff81864ec7: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e001)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8182db60-ffffffff8182db77: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b60e1)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818b5c40-ffffffff818b5c57: cpufreq_cpu_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_cpu_put(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2391)
Location: drivers/cpufreq/cpufreq.c:241
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_get_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get_max
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_release
Direct callers:
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818d1ef0-ffffffff818d1f07: cpufreq_cpu_put (STB_GLOBAL)
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
