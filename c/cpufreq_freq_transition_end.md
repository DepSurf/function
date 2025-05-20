# Function: <code>cpufreq_freq_transition_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816aeee0)
Location: drivers/cpufreq/cpufreq.c:457
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff816aeee0-ffffffff816aef89: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817107d0)
Location: drivers/cpufreq/cpufreq.c:412
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff817107d0-ffffffff81710879: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817427e0)
Location: drivers/cpufreq/cpufreq.c:412
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff817427e0-ffffffff81742889: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81760e70)
Location: drivers/cpufreq/cpufreq.c:412
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81760e70-ffffffff81760f08: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6e30)
Location: drivers/cpufreq/cpufreq.c:418
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff817d6e30-ffffffff817d6eca: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f970)
Location: drivers/cpufreq/cpufreq.c:403
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8181f970-ffffffff8181fa07: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b810)
Location: drivers/cpufreq/cpufreq.c:403
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/powernow-k8.c:powernowk8_target_fn
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff8184b810-ffffffff8184b8a7: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:433
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
ffffffff81892398-ffffffff818923ab: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff8188e870-ffffffff8188e907: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c1390)
Location: drivers/cpufreq/cpufreq.c:436
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
ffffffff818c1390-ffffffff818c142a: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81994850)
Location: drivers/cpufreq/cpufreq.c:441
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
ffffffff81994850-ffffffff819948ea: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819977a0)
Location: drivers/cpufreq/cpufreq.c:443
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
ffffffff819977a0-ffffffff8199783a: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c110)
Location: drivers/cpufreq/cpufreq.c:440
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
ffffffff8197c110-ffffffff8197c1aa: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:440
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
ffffffff81d2bf15-ffffffff81d2bf2a: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff81a25370-ffffffff81a25427: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:441
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
ffffffff81ef8156-ffffffff81ef816b: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff81b8e770-ffffffff81b8e849: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:441
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
ffffffff820a8d07-ffffffff820a8d1c: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff81d2eac0-ffffffff81d2eb99: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:446
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
ffffffff82129f20-ffffffff82129f35: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff81d97bd0-ffffffff81d97cc3: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:447
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
ffffffff8220bcfa-ffffffff8220bd0f: cpufreq_freq_transition_end.cold (STB_LOCAL)
ffffffff81e4f850-ffffffff81e4f943: cpufreq_freq_transition_end (STB_GLOBAL)
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
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1e818)
Location: drivers/cpufreq/cpufreq.c:436
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
ffff800010b1e818-ffff800010b1e8c4: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf8e2c)
Location: drivers/cpufreq/cpufreq.c:436
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
c0bf8e2c-c0bf8ed0: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c11540)
Location: drivers/cpufreq/cpufreq.c:436
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
```
**Symbols:**

```
c000000000c11540-c000000000c11614: cpufreq_freq_transition_end (STB_GLOBAL)
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
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865ab0)
Location: drivers/cpufreq/cpufreq.c:436
Inline: False
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
ffffffff81865ab0-ffffffff81865b4a: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e760)
Location: drivers/cpufreq/cpufreq.c:436
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
ffffffff8182e760-ffffffff8182e7fa: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6840)
Location: drivers/cpufreq/cpufreq.c:436
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
ffffffff818b6840-ffffffff818b68da: cpufreq_freq_transition_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy *policy, struct cpufreq_freqs *freqs, int transition_failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2b10)
Location: drivers/cpufreq/cpufreq.c:436
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
ffffffff818d2b10-ffffffff818d2baa: cpufreq_freq_transition_end (STB_GLOBAL)
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
