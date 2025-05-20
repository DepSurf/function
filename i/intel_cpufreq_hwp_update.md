# Function: <code>intel_cpufreq_hwp_update</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81986ed0)
Location: drivers/cpufreq/intel_pstate.c:2509
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81986ed0-ffffffff81986f42: intel_cpufreq_hwp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30b30)
Location: drivers/cpufreq/intel_pstate.c:2680
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81a30b30-ffffffff81a30ba2: intel_cpufreq_hwp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9cb80)
Location: drivers/cpufreq/intel_pstate.c:2846
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81b9cb80-ffffffff81b9cc3f: intel_cpufreq_hwp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3e6b0)
Location: drivers/cpufreq/intel_pstate.c:2810
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81d3e6b0-ffffffff81d3e76f: intel_cpufreq_hwp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da9230)
Location: drivers/cpufreq/intel_pstate.c:2836
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81da9230-ffffffff81da92ef: intel_cpufreq_hwp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_cpufreq_hwp_update(struct cpudata *cpu, u32 min, u32 max, u32 desired, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e61850)
Location: drivers/cpufreq/intel_pstate.c:2860
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate
```
**Symbols:**

```
ffffffff81e61850-ffffffff81e6190f: intel_cpufreq_hwp_update (STB_LOCAL)
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
