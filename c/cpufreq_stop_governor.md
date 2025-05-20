# Function: <code>cpufreq_stop_governor</code>

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
In drivers/cpufreq/cpufreq.c (ffffffff8171136f)
Location: drivers/cpufreq/cpufreq.c:2086
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817112c0-ffffffff81711309: cpufreq_stop_governor.part.12 (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81744807)
Location: drivers/cpufreq/cpufreq.c:2058
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81743260-ffffffff817432a6: cpufreq_stop_governor.part.10 (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff81763870)
Location: drivers/cpufreq/cpufreq.c:2061
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81761920-ffffffff81761966: cpufreq_stop_governor.part.10 (STB_LOCAL)
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
In drivers/cpufreq/cpufreq.c (ffffffff817d9865)
Location: drivers/cpufreq/cpufreq.c:2094
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff817d7900-ffffffff817d7949: cpufreq_stop_governor.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81820320)
Location: drivers/cpufreq/cpufreq.c:2093
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81820320-ffffffff8182037c: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c1d0)
Location: drivers/cpufreq/cpufreq.c:2094
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8184c1d0-ffffffff8184c22c: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f1c0)
Location: drivers/cpufreq/cpufreq.c:2244
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8188f1c0-ffffffff8188f21f: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c11a0)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818c11a0-ffffffff818c11ff: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81993020)
Location: drivers/cpufreq/cpufreq.c:2295
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
```
**Symbols:**

```
ffffffff81993020-ffffffff81993081: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819986e0)
Location: drivers/cpufreq/cpufreq.c:2371
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff819986e0-ffffffff81998741: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d200)
Location: drivers/cpufreq/cpufreq.c:2377
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8197d200-ffffffff8197d261: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a2629e)
Location: drivers/cpufreq/cpufreq.c:2379
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81d2c084-ffffffff81d2c098: cpufreq_stop_governor.cold (STB_LOCAL)
ffffffff81a26270-ffffffff81a262dc: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8fc80)
Location: drivers/cpufreq/cpufreq.c:2419
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81ef82f1-ffffffff81ef8306: cpufreq_stop_governor.cold (STB_LOCAL)
ffffffff81b8fc50-ffffffff81b8fcc9: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2fdd0)
Location: drivers/cpufreq/cpufreq.c:2416
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff820a8dc8-ffffffff820a8ddd: cpufreq_stop_governor.cold (STB_LOCAL)
ffffffff81d2fda0-ffffffff81d2fe22: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d990b0)
Location: drivers/cpufreq/cpufreq.c:2423
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff82129fe1-ffffffff82129ff6: cpufreq_stop_governor.cold (STB_LOCAL)
ffffffff81d99080-ffffffff81d99102: cpufreq_stop_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e50d30)
Location: drivers/cpufreq/cpufreq.c:2464
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8220bdbb-ffffffff8220bdd0: cpufreq_stop_governor.cold (STB_LOCAL)
ffffffff81e50d00-ffffffff81e50d82: cpufreq_stop_governor (STB_GLOBAL)
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
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1dcd8)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff800010b1dcd8-ffff800010b1dd54: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf8b94)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0bf8b94-c0bf8c1c: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c10fd0)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c000000000c10fd0-c000000000c11098: cpufreq_stop_governor (STB_LOCAL)
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
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818658c0)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818658c0-ffffffff8186591f: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e570)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8182e570-ffffffff8182e5cf: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6650)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818b6650-ffffffff818b66af: cpufreq_stop_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2900)
Location: drivers/cpufreq/cpufreq.c:2258
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818d2900-ffffffff818d295f: cpufreq_stop_governor (STB_LOCAL)
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
