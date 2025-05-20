# Function: <code>intel_cpufreq_update_pstate</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3a10)
Location: drivers/cpufreq/intel_pstate.c:2565
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff819a3a10-ffffffff819a3b10: intel_cpufreq_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81988650)
Location: drivers/cpufreq/intel_pstate.c:2544
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81988650-ffffffff81988745: intel_cpufreq_update_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2715
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81a326e0-ffffffff81a327eb: intel_cpufreq_update_pstate (STB_LOCAL)
ffffffff81d2cc5a-ffffffff81d2cc6f: intel_cpufreq_update_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2881
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81b9ec40-ffffffff81b9ed68: intel_cpufreq_update_pstate (STB_LOCAL)
ffffffff81ef9005-ffffffff81ef901a: intel_cpufreq_update_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2845
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81d40210-ffffffff81d40338: intel_cpufreq_update_pstate (STB_LOCAL)
ffffffff820a929b-ffffffff820a92b0: intel_cpufreq_update_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2871
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81daad80-ffffffff81daaea8: intel_cpufreq_update_pstate (STB_LOCAL)
ffffffff8212a6a4-ffffffff8212a6b9: intel_cpufreq_update_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_update_pstate(struct cpufreq_policy *policy, int target_pstate, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2895
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_target
```
**Symbols:**

```
ffffffff81e62ea0-ffffffff81e62fc8: intel_cpufreq_update_pstate (STB_LOCAL)
ffffffff8220c466-ffffffff8220c47b: intel_cpufreq_update_pstate.cold (STB_LOCAL)
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
