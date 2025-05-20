# Function: <code>intel_pstate_update_perf_limits</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct perf_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174d750)
Location: drivers/cpufreq/intel_pstate.c:1969
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8174d750-ffffffff8174d853: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176bed0)
Location: drivers/cpufreq/intel_pstate.c:1959
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8176bed0-ffffffff8176c0ea: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e1d40)
Location: drivers/cpufreq/intel_pstate.c:1722
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff817e1d40-ffffffff817e1f5a: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182aac0)
Location: drivers/cpufreq/intel_pstate.c:1905
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8182aac0-ffffffff8182acbb: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818566d0)
Location: drivers/cpufreq/intel_pstate.c:1968
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818566d0-ffffffff818568cb: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpufreq_policy *policy, struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81899da0)
Location: drivers/cpufreq/intel_pstate.c:1993
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81899da0-ffffffff81899f91: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cbd90)
Location: drivers/cpufreq/intel_pstate.c:2039
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818cbd90-ffffffff818cbf9e: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199de20)
Location: drivers/cpufreq/intel_pstate.c:2047
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8199de20-ffffffff8199e026: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a2530)
Location: drivers/cpufreq/intel_pstate.c:2197
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff819a2530-ffffffff819a2754: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81986ce0)
Location: drivers/cpufreq/intel_pstate.c:2194
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81986ce0-ffffffff81986ec8: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2355
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81a30240-ffffffff81a303f7: intel_pstate_update_perf_limits (STB_LOCAL)
ffffffff81d2c9d3-ffffffff81d2c9e8: intel_pstate_update_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2525
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81b9b4f0-ffffffff81b9b6bd: intel_pstate_update_perf_limits (STB_LOCAL)
ffffffff81ef8c7b-ffffffff81ef8c90: intel_pstate_update_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2489
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81d3ce30-ffffffff81d3cff0: intel_pstate_update_perf_limits (STB_LOCAL)
ffffffff820a905d-ffffffff820a9072: intel_pstate_update_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2510
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81da7a00-ffffffff81da7bc0: intel_pstate_update_perf_limits (STB_LOCAL)
ffffffff8212a47a-ffffffff8212a48f: intel_pstate_update_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2535
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81e61260-ffffffff81e6146d: intel_pstate_update_perf_limits (STB_LOCAL)
ffffffff8220c2ed-ffffffff8220c302: intel_pstate_update_perf_limits.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186f990)
Location: drivers/cpufreq/intel_pstate.c:2039
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8186f990-ffffffff8186fb9e: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81838f10)
Location: drivers/cpufreq/intel_pstate.c:2039
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81838f10-ffffffff8183911e: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1240)
Location: drivers/cpufreq/intel_pstate.c:2039
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818c1240-ffffffff818c144e: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pstate_update_perf_limits(struct cpudata *cpu, unsigned int policy_min, unsigned int policy_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd550)
Location: drivers/cpufreq/intel_pstate.c:2039
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818dd550-ffffffff818dd75e: intel_pstate_update_perf_limits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpudata *cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct perf_limits *limits</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int policy_min</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int policy_max</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpufreq_policy *policy</code>
</li>
<li>
<b>Param reordered. </b>
<code>policy, cpu</code> ➡️ <code>cpu, policy_min, policy_max</code>
</li>
</ul>
</details>
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
