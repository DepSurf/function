# Function: <code>cpufreq_freq_transition_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816aeda0)
Location: drivers/cpufreq/cpufreq.c:423
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff816aeda0-ffffffff816aeed5: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710690)
Location: drivers/cpufreq/cpufreq.c:378
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff81710690-ffffffff817107c5: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817426b0)
Location: drivers/cpufreq/cpufreq.c:378
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff817426b0-ffffffff817427de: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81760d50)
Location: drivers/cpufreq/cpufreq.c:378
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81760d50-ffffffff81760e6f: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6d10)
Location: drivers/cpufreq/cpufreq.c:384
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff817d6d10-ffffffff817d6e2f: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820eb0)
Location: drivers/cpufreq/cpufreq.c:369
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81820eb0-ffffffff81820fc8: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184cc20)
Location: drivers/cpufreq/cpufreq.c:369
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8184cc20-ffffffff8184cd38: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:399
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8189248b-ffffffff8189249e: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff8188feb0-ffffffff8188ffd5: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c20b0)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff818c20b0-ffffffff818c21d8: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994720)
Location: drivers/cpufreq/cpufreq.c:407
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_intermediate
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81994720-ffffffff81994846: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81997670)
Location: drivers/cpufreq/cpufreq.c:409
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_intermediate
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81997670-ffffffff81997796: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c3d0)
Location: drivers/cpufreq/cpufreq.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8197c3d0-ffffffff8197c4f6: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:406
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81d2bf42-ffffffff81d2bf7e: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff81a25640-ffffffff81a25790: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:407
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_target
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81ef816b-ffffffff81ef81aa: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff81b8e850-ffffffff81b8e9d6: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:407
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_target
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff820a8d1c-ffffffff820a8d5b: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff81d2ebb0-ffffffff81d2ed36: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:412
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff82129f35-ffffffff82129f74: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff81d97ce0-ffffffff81d97e66: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:413
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:__target_index
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8220bd0f-ffffffff8220bd4e: cpufreq_freq_transition_begin.cold (STB_LOCAL)
ffffffff81e4f960-ffffffff81e4fae6: cpufreq_freq_transition_begin (STB_GLOBAL)
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
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1e950)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
ffff800010b1e950-ffff800010b1eac0: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf8ed0)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
c0bf8ed0-c0bf903c: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c11340)
Location: drivers/cpufreq/cpufreq.c:402
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
c000000000c11340-c000000000c11540: cpufreq_freq_transition_begin (STB_GLOBAL)
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
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818667d0)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff818667d0-ffffffff818668f8: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182f480)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8182f480-ffffffff8182f5a8: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b7560)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff818b7560-ffffffff818b7688: cpufreq_freq_transition_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_freq_transition_begin(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2bb0)
Location: drivers/cpufreq/cpufreq.c:402
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff818d2bb0-ffffffff818d2ccc: cpufreq_freq_transition_begin (STB_GLOBAL)
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
