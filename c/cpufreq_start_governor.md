# Function: <code>cpufreq_start_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81712ffe)
Location: drivers/cpufreq/cpufreq.c:2059
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817115a0-ffffffff81711631: cpufreq_start_governor.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81744e60)
Location: drivers/cpufreq/cpufreq.c:2031
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81743350-ffffffff817433db: cpufreq_start_governor.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763894)
Location: drivers/cpufreq/cpufreq.c:2034
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81761a10-ffffffff81761a91: cpufreq_start_governor.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9889)
Location: drivers/cpufreq/cpufreq.c:2067
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817d79f0-ffffffff817d7a77: cpufreq_start_governor.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818210f0)
Location: drivers/cpufreq/cpufreq.c:2066
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818210f0-ffffffff81821190: cpufreq_start_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184ce60)
Location: drivers/cpufreq/cpufreq.c:2067
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8184ce60-ffffffff8184cf00: cpufreq_start_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8189149a)
Location: drivers/cpufreq/cpufreq.c:2217
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818900d0-ffffffff8189015b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c366d)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818c22d0-ffffffff818c235b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995a75)
Location: drivers/cpufreq/cpufreq.c:2268
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
```
**Symbols:**

```
ffffffff819949e0-ffffffff81994a6b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998932)
Location: drivers/cpufreq/cpufreq.c:2344
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81997930-ffffffff819979bb: cpufreq_start_governor.part.0 (STB_LOCAL)
ffffffff819986b0-ffffffff819986d9: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d020)
Location: drivers/cpufreq/cpufreq.c:2350
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8197d020-ffffffff8197d0c0: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a2609c)
Location: drivers/cpufreq/cpufreq.c:2352
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81d2c025-ffffffff81d2c039: cpufreq_start_governor.cold (STB_LOCAL)
ffffffff81a26070-ffffffff81a26115: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2392
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81ef8291-ffffffff81ef82a6: cpufreq_start_governor.cold (STB_LOCAL)
ffffffff81b8fa40-ffffffff81b8faef: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2389
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff820a8d9e-ffffffff820a8db3: cpufreq_start_governor.cold (STB_LOCAL)
ffffffff81d2fb20-ffffffff81d2fbe1: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2396
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff82129fb7-ffffffff82129fcc: cpufreq_start_governor.cold (STB_LOCAL)
ffffffff81d98e00-ffffffff81d98ec1: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2437
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8220bd91-ffffffff8220bda6: cpufreq_start_governor.cold (STB_LOCAL)
ffffffff81e50a80-ffffffff81e50b41: cpufreq_start_governor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b21050)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff800010b1ebd0-ffff800010b1ec78: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_start_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9cbc)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0bf9cbc-c0bf9d90: cpufreq_start_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14d40)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c000000000c12670-c000000000c12758: cpufreq_start_governor.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867d8d)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818669f0-ffffffff81866a7b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81830a3d)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8182f6a0-ffffffff8182f72b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8b1d)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818b7780-ffffffff818b780b: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4df9)
Location: drivers/cpufreq/cpufreq.c:2231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818d3660-ffffffff818d36eb: cpufreq_start_governor.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
