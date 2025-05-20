# Function: <code>cpufreq_frequency_table_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table, unsigned int target_freq, unsigned int relation, unsigned int *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff816b25c0)
Location: drivers/cpufreq/freq_table.c:120
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff816b25c0-ffffffff816b27d5: cpufreq_frequency_table_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817117c8)
Location: include/linux/cpufreq.h:837
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715df9)
Location: include/linux/cpufreq.h:837
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81743fbf)
Location: include/linux/cpufreq.h:841
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747b7a)
Location: include/linux/cpufreq.h:841
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8176252f)
Location: include/linux/cpufreq.h:845
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817661fa)
Location: include/linux/cpufreq.h:845
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d8522)
Location: include/linux/cpufreq.h:865
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dc19a)
Location: include/linux/cpufreq.h:865
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81821262)
Location: include/linux/cpufreq.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824e48)
Location: include/linux/cpufreq.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184cfd2)
Location: include/linux/cpufreq.h:890
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850d08)
Location: include/linux/cpufreq.h:890
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81890236)
Location: include/linux/cpufreq.h:919
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81894248)
Location: include/linux/cpufreq.h:919
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c2436)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c6268)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819937c5)
Location: include/linux/cpufreq.h:927
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff819983b8)
Location: include/linux/cpufreq.h:927
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff81993c00-ffffffff81993e46: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff81996753-ffffffff81996771: cpufreq_frequency_table_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81997cdd)
Location: include/linux/cpufreq.h:980
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b4db)
Location: include/linux/cpufreq.h:980
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c95b)
Location: include/linux/cpufreq.h:974
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff819801b8)
Location: include/linux/cpufreq.h:974
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a247f0)
Location: include/linux/cpufreq.h:971
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a29358)
Location: include/linux/cpufreq.h:971
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8fdf8)
Location: include/linux/cpufreq.h:1026
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpufreq.h:1026
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff81b8ded0-ffffffff81b8e25a: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff81ef80b7-ffffffff81ef80d8: cpufreq_frequency_table_target.cold (STB_LOCAL)
ffffffff81b932e0-ffffffff81b9366a: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff81ef847b-ffffffff81ef849c: cpufreq_frequency_table_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ff46)
Location: include/linux/cpufreq.h:1026
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpufreq.h:1026
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff81d2d9a0-ffffffff81d2dd47: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff820a8ccb-ffffffff820a8cec: cpufreq_frequency_table_target.cold (STB_LOCAL)
ffffffff81d33960-ffffffff81d33d07: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff820a8e8a-ffffffff820a8eab: cpufreq_frequency_table_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d99226)
Location: include/linux/cpufreq.h:1029
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpufreq.h:1029
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff81d96c20-ffffffff81d96fbc: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff82129ee4-ffffffff82129f05: cpufreq_frequency_table_target.cold (STB_LOCAL)
ffffffff81d9ccf0-ffffffff81d9d08c: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff8212a124-ffffffff8212a145: cpufreq_frequency_table_target.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_frequency_table_target(struct cpufreq_policy *policy, unsigned int target_freq, unsigned int relation);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e50ea6)
Location: include/linux/cpufreq.h:1024
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpufreq.h:1024
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
**Symbols:**

```
ffffffff81e4e880-ffffffff81e4ec1c: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff8220bcbe-ffffffff8220bcdf: cpufreq_frequency_table_target.cold (STB_LOCAL)
ffffffff81e549b0-ffffffff81e54d4c: cpufreq_frequency_table_target (STB_LOCAL)
ffffffff8220befe-ffffffff8220bf1f: cpufreq_frequency_table_target.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1ee44)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24314)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9408)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe380)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c11b3c)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18cdc)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81866b56)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a988)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182f806)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833638)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b78e6)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb718)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2ee6)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_resolve_freq
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7a08)
Location: include/linux/cpufreq.h:925
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
