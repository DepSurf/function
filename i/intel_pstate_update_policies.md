# Function: <code>intel_pstate_update_policies</code>

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
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8174dbb0)
Location: drivers/cpufreq/intel_pstate.c:987
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
```
**Symbols:**

```
ffffffff8174dbb0-ffffffff8174dbf5: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c170)
Location: drivers/cpufreq/intel_pstate.c:906
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff8176c170-ffffffff8176c1b4: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e1fe0)
Location: drivers/cpufreq/intel_pstate.c:797
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff817e1fe0-ffffffff817e201a: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182ad40)
Location: drivers/cpufreq/intel_pstate.c:828
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff8182ad40-ffffffff8182ad7a: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81856cb0)
Location: drivers/cpufreq/intel_pstate.c:890
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff81856cb0-ffffffff81856cea: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a3f0)
Location: drivers/cpufreq/intel_pstate.c:890
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff8189a3f0-ffffffff8189a429: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc3f0)
Location: drivers/cpufreq/intel_pstate.c:889
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff818cc3f0-ffffffff818cc429: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199f4ef)
Location: drivers/cpufreq/intel_pstate.c:895
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a1cbf)
Location: drivers/cpufreq/intel_pstate.c:997
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81986c9f)
Location: drivers/cpufreq/intel_pstate.c:999
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30a5f)
Location: drivers/cpufreq/intel_pstate.c:1099
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c7d1)
Location: drivers/cpufreq/intel_pstate.c:1129
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d690)
Location: drivers/cpufreq/intel_pstate.c:1104
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff81d3d690-ffffffff81d3d6da: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da8230)
Location: drivers/cpufreq/intel_pstate.c:1124
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff81da8230-ffffffff81da827a: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e60010)
Location: drivers/cpufreq/intel_pstate.c:1148
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff81e60010-ffffffff81e6005a: intel_pstate_update_policies (STB_LOCAL)
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
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8186fff0)
Location: drivers/cpufreq/intel_pstate.c:889
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff8186fff0-ffffffff81870029: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839570)
Location: drivers/cpufreq/intel_pstate.c:889
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff81839570-ffffffff818395a9: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c18a0)
Location: drivers/cpufreq/intel_pstate.c:889
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff818c18a0-ffffffff818c18d9: intel_pstate_update_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pstate_update_policies();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ddbb0)
Location: drivers/cpufreq/intel_pstate.c:889
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff818ddbb0-ffffffff818ddbe9: intel_pstate_update_policies (STB_LOCAL)
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
