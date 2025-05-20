# Function: <code>cpufreq_update_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b0ac0)
Location: drivers/cpufreq/cpufreq.c:2205
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
```
**Symbols:**

```
ffffffff816b0ac0-ffffffff816b0c5d: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817134e0)
Location: drivers/cpufreq/cpufreq.c:2293
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
```
**Symbols:**

```
ffffffff817134e0-ffffffff81713613: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817452f0)
Location: drivers/cpufreq/cpufreq.c:2265
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff817452f0-ffffffff81745423: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81763a20)
Location: drivers/cpufreq/cpufreq.c:2268
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff81763a20-ffffffff81763b44: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9a10)
Location: drivers/cpufreq/cpufreq.c:2301
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff817d9a10-ffffffff817d9b34: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81822500)
Location: drivers/cpufreq/cpufreq.c:2299
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff81822500-ffffffff8182261a: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184e3e0)
Location: drivers/cpufreq/cpufreq.c:2302
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff8184e3e0-ffffffff8184e4fa: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2472
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff818925ba-ffffffff818925cd: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81891700-ffffffff8189176e: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c3860)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff818c3860-ffffffff818c38ce: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995d10)
Location: drivers/cpufreq/cpufreq.c:2506
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81995d10-ffffffff81995d9e: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998bd0)
Location: drivers/cpufreq/cpufreq.c:2583
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81998bd0-ffffffff81998c9c: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197d620)
Location: drivers/cpufreq/cpufreq.c:2589
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff8197d620-ffffffff8197d69f: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2598
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81d2c0ac-ffffffff81d2c0c1: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81a266a0-ffffffff81a26727: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2638
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
```
**Symbols:**

```
ffffffff81ef8351-ffffffff81ef8366: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81b90360-ffffffff81b903f2: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2635
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff820a8e4d-ffffffff820a8e62: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81d304f0-ffffffff81d305af: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2642
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff8212a066-ffffffff8212a07b: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81d99790-ffffffff81d99848: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2682
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff8220be40-ffffffff8220be55: cpufreq_update_policy.cold (STB_LOCAL)
ffffffff81e51400-ffffffff81e514b8: cpufreq_update_policy (STB_GLOBAL)
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
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b21238)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
```
**Symbols:**

```
ffff800010b21238-ffff800010b212d0: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfb8dc)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
```
**Symbols:**

```
c0bfb8dc-c0bfb994: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c14fe0)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
```
**Symbols:**

```
c000000000c14fe0-c000000000c150b4: cpufreq_update_policy (STB_GLOBAL)
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
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867f80)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff81867f80-ffffffff81867fee: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81830c30)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff81830c30-ffffffff81830c9e: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b8d10)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff818b8d10-ffffffff818b8d7e: cpufreq_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_update_policy(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4ff0)
Location: drivers/cpufreq/cpufreq.c:2466
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
```
**Symbols:**

```
ffffffff818d4ff0-ffffffff818d505e: cpufreq_update_policy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
