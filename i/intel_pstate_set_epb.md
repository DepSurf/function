# Function: <code>intel_pstate_set_epb</code>

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
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174da70)
Location: drivers/cpufreq/intel_pstate.c:682
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8174da70-ffffffff8174dafd: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c920)
Location: drivers/cpufreq/intel_pstate.c:622
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8176c920-ffffffff8176c9af: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2610)
Location: drivers/cpufreq/intel_pstate.c:513
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff817e2610-ffffffff817e269f: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b4a0)
Location: drivers/cpufreq/intel_pstate.c:537
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8182b4a0-ffffffff8182b52f: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857430)
Location: drivers/cpufreq/intel_pstate.c:560
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81857430-ffffffff818574bf: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a2e0)
Location: drivers/cpufreq/intel_pstate.c:560
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8189a2e0-ffffffff8189a371: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc2e0)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff818cc2e0-ffffffff818cc371: intel_pstate_set_epb (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff8199e9b0)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8199e9b0-ffffffff8199ea2f: intel_pstate_set_epb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0aa0)
Location: drivers/cpufreq/intel_pstate.c:552
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff819a0aa0-ffffffff819a0b31: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985710)
Location: drivers/cpufreq/intel_pstate.c:552
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81985710-ffffffff819857a1: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2f340)
Location: drivers/cpufreq/intel_pstate.c:625
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81a2f340-ffffffff81a2f3d1: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ae20)
Location: drivers/cpufreq/intel_pstate.c:638
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81b9ae20-ffffffff81b9aec3: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3c6a0)
Location: drivers/cpufreq/intel_pstate.c:613
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81d3c6a0-ffffffff81d3c743: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7270)
Location: drivers/cpufreq/intel_pstate.c:631
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81da7270-ffffffff81da7313: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f170)
Location: drivers/cpufreq/intel_pstate.c:655
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81e5f170-ffffffff81e5f213: intel_pstate_set_epb (STB_LOCAL)
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
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186fee0)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff8186fee0-ffffffff8186ff71: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839460)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff81839460-ffffffff818394f1: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1790)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff818c1790-ffffffff818c1821: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pstate_set_epb(int cpu, s16 pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ddaa0)
Location: drivers/cpufreq/intel_pstate.c:561
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
```
**Symbols:**

```
ffffffff818ddaa0-ffffffff818ddb31: intel_pstate_set_epb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
