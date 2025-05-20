# Function: <code>intel_pstate_init_acpi_perf_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c8aa)
Location: drivers/cpufreq/intel_pstate.c:374
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f081)
Location: drivers/cpufreq/intel_pstate.c:461
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d4fa)
Location: drivers/cpufreq/intel_pstate.c:422
Inline: True
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e32ba)
Location: drivers/cpufreq/intel_pstate.c:363
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c7ad)
Location: drivers/cpufreq/intel_pstate.c:382
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81858391)
Location: drivers/cpufreq/intel_pstate.c:398
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189bc43)
Location: drivers/cpufreq/intel_pstate.c:398
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cddb3)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e790)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: False
```
**Symbols:**

```
ffffffff8199e790-ffffffff8199e9ad: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a10b0)
Location: drivers/cpufreq/intel_pstate.c:390
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff819a10b0-ffffffff819a1209: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff819a1280-ffffffff819a1353: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81985be0)
Location: drivers/cpufreq/intel_pstate.c:390
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81985be0-ffffffff81985d39: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff81985db0-ffffffff81985e83: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:404
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81a2fa20-ffffffff81a2fb85: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff81d2c97f-ffffffff81d2c993: intel_pstate_init_acpi_perf_limits.part.0.cold (STB_LOCAL)
ffffffff81a2fb90-ffffffff81a2fc7e: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
ffffffff81d2c9ab-ffffffff81d2c9bf: intel_pstate_init_acpi_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:417
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81b9b780-ffffffff81b9b92a: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff81ef8cab-ffffffff81ef8cbf: intel_pstate_init_acpi_perf_limits.part.0.cold (STB_LOCAL)
ffffffff81b9b930-ffffffff81b9ba7d: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
ffffffff81ef8cdf-ffffffff81ef8cf4: intel_pstate_init_acpi_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:409
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81d3d0e0-ffffffff81d3d28a: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff820a908d-ffffffff820a90a1: intel_pstate_init_acpi_perf_limits.part.0.cold (STB_LOCAL)
ffffffff81d3d2d0-ffffffff81d3d41d: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
ffffffff820a90a1-ffffffff820a90b6: intel_pstate_init_acpi_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7cb0)
Location: drivers/cpufreq/intel_pstate.c:436
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81da7cb0-ffffffff81da7e15: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff81da7e60-ffffffff81da7fbc: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
ffffffff8212a4aa-ffffffff8212a4bf: intel_pstate_init_acpi_perf_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_init_acpi_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f9e0)
Location: drivers/cpufreq/intel_pstate.c:439
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_online
```
**Symbols:**

```
ffffffff81e5f9e0-ffffffff81e5fb45: intel_pstate_init_acpi_perf_limits.part.0 (STB_LOCAL)
ffffffff81e5fb90-ffffffff81e5fcec: intel_pstate_init_acpi_perf_limits (STB_LOCAL)
ffffffff8220c26f-ffffffff8220c284: intel_pstate_init_acpi_perf_limits.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818719b3)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8183b19a)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c3263)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818df5c3)
Location: drivers/cpufreq/intel_pstate.c:399
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
