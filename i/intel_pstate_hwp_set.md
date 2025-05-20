# Function: <code>intel_pstate_hwp_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_pstate_hwp_set();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba100)
Location: drivers/cpufreq/intel_pstate.c:283
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff816ba100-ffffffff816ba243: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_pstate_hwp_set(const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171bba0)
Location: drivers/cpufreq/intel_pstate.c:554
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
  - drivers/cpufreq/intel_pstate.c:store_min_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_max_perf_pct
  - drivers/cpufreq/intel_pstate.c:store_no_turbo
```
**Symbols:**

```
ffffffff8171bba0-ffffffff8171bcd0: intel_pstate_hwp_set (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174e1a0)
Location: drivers/cpufreq/intel_pstate.c:860
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8174e1a0-ffffffff8174e3c4: intel_pstate_hwp_set.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c9b0)
Location: drivers/cpufreq/intel_pstate.c:810
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8176c9b0-ffffffff8176cafa: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e26a0)
Location: drivers/cpufreq/intel_pstate.c:701
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff817e26a0-ffffffff817e27ea: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b530)
Location: drivers/cpufreq/intel_pstate.c:726
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8182b530-ffffffff8182b681: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818574c0)
Location: drivers/cpufreq/intel_pstate.c:766
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818574c0-ffffffff81857611: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189acf0)
Location: drivers/cpufreq/intel_pstate.c:766
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8189acf0-ffffffff8189ae55: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ccea0)
Location: drivers/cpufreq/intel_pstate.c:767
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818ccea0-ffffffff818cd005: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199ebb0)
Location: drivers/cpufreq/intel_pstate.c:773
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8199ebb0-ffffffff8199ed13: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0b40)
Location: drivers/cpufreq/intel_pstate.c:837
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff819a0b40-ffffffff819a0c7b: intel_pstate_hwp_set (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff819872dd)
Location: drivers/cpufreq/intel_pstate.c:839
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a321e0)
Location: drivers/cpufreq/intel_pstate.c:926
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e320)
Location: drivers/cpufreq/intel_pstate.c:949
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40779)
Location: drivers/cpufreq/intel_pstate.c:924
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab30a)
Location: drivers/cpufreq/intel_pstate.c:944
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e633be)
Location: drivers/cpufreq/intel_pstate.c:968
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
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
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870aa0)
Location: drivers/cpufreq/intel_pstate.c:767
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81870aa0-ffffffff81870c05: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8183a020)
Location: drivers/cpufreq/intel_pstate.c:767
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8183a020-ffffffff8183a185: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c2350)
Location: drivers/cpufreq/intel_pstate.c:767
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818c2350-ffffffff818c24b5: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pstate_hwp_set(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de660)
Location: drivers/cpufreq/intel_pstate.c:767
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff818de660-ffffffff818de7c5: intel_pstate_hwp_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *cpumask</code>
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
