# Function: <code>intel_pstate_get_hwp_max</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176bfad)
Location: drivers/cpufreq/intel_pstate.c:796
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e1e1d)
Location: drivers/cpufreq/intel_pstate.c:687
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182aa30)
Location: drivers/cpufreq/intel_pstate.c:711
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8182aa30-ffffffff8182aabc: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81856640)
Location: drivers/cpufreq/intel_pstate.c:751
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81856640-ffffffff818566cc: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81899d10)
Location: drivers/cpufreq/intel_pstate.c:751
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81899d10-ffffffff81899d9c: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cbd00)
Location: drivers/cpufreq/intel_pstate.c:752
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818cbd00-ffffffff818cbd8c: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199dd90)
Location: drivers/cpufreq/intel_pstate.c:758
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_cpu_pstates
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8199dd90-ffffffff8199de1d: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a2ef0)
Location: drivers/cpufreq/intel_pstate.c:822
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186f900)
Location: drivers/cpufreq/intel_pstate.c:752
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff8186f900-ffffffff8186f98c: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81838e80)
Location: drivers/cpufreq/intel_pstate.c:752
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff81838e80-ffffffff81838f0c: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c11b0)
Location: drivers/cpufreq/intel_pstate.c:752
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818c11b0-ffffffff818c123c: intel_pstate_get_hwp_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pstate_get_hwp_max(unsigned int cpu, int *phy_max, int *current_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd4c0)
Location: drivers/cpufreq/intel_pstate.c:752
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_perf_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:update_qos_request
```
**Symbols:**

```
ffffffff818dd4c0-ffffffff818dd54c: intel_pstate_get_hwp_max (STB_LOCAL)
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
