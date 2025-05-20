# Function: <code>intel_cpufreq_cpu_offline</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_offline(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2504
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81a308b0-ffffffff81a309eb: intel_cpufreq_cpu_offline (STB_LOCAL)
ffffffff81d2c9ea-ffffffff81d2ca14: intel_cpufreq_cpu_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_offline(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2670
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81b9c250-ffffffff81b9c3c0: intel_cpufreq_cpu_offline (STB_LOCAL)
ffffffff81ef8d33-ffffffff81ef8d5d: intel_cpufreq_cpu_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_offline(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2634
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81d3ddd0-ffffffff81d3df40: intel_cpufreq_cpu_offline (STB_LOCAL)
ffffffff820a90cb-ffffffff820a90f5: intel_cpufreq_cpu_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_offline(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2660
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81da8970-ffffffff81da8ae7: intel_cpufreq_cpu_offline (STB_LOCAL)
ffffffff8212a4d4-ffffffff8212a4fe: intel_cpufreq_cpu_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_cpufreq_cpu_offline(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2684
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
```
**Symbols:**

```
ffffffff81e605b0-ffffffff81e60727: intel_cpufreq_cpu_offline (STB_LOCAL)
ffffffff8220c299-ffffffff8220c2c3: intel_cpufreq_cpu_offline.cold (STB_LOCAL)
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
