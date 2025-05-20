# Function: <code>intel_pstate_get_cpu_pstates</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba7d7)
Location: drivers/cpufreq/intel_pstate.c:846
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c72b)
Location: drivers/cpufreq/intel_pstate.c:1151
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174e77b)
Location: drivers/cpufreq/intel_pstate.c:1609
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176ceec)
Location: drivers/cpufreq/intel_pstate.c:1546
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e2e8b)
Location: drivers/cpufreq/intel_pstate.c:1361
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182b96b)
Location: drivers/cpufreq/intel_pstate.c:1422
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff818578eb)
Location: drivers/cpufreq/intel_pstate.c:1485
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189b44c)
Location: drivers/cpufreq/intel_pstate.c:1514
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff818cd5fc)
Location: drivers/cpufreq/intel_pstate.c:1560
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_get_cpu_pstates(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8199eeb0)
Location: drivers/cpufreq/intel_pstate.c:1567
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff8199eeb0-ffffffff8199efcb: intel_pstate_get_cpu_pstates (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a2b20)
Location: drivers/cpufreq/intel_pstate.c:1714
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff819a2b20-ffffffff819a2c5d: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff819863d2)
Location: drivers/cpufreq/intel_pstate.c:1714
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81a30590)
Location: drivers/cpufreq/intel_pstate.c:1857
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81a30590-ffffffff81a30715: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c050)
Location: drivers/cpufreq/intel_pstate.c:2026
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81b9c050-ffffffff81b9c1ce: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d850)
Location: drivers/cpufreq/intel_pstate.c:1988
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81d3d850-ffffffff81d3d9d8: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81da87d0)
Location: drivers/cpufreq/intel_pstate.c:2018
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81da87d0-ffffffff81da8958: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81e60c60)
Location: drivers/cpufreq/intel_pstate.c:2042
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
**Symbols:**

```
ffffffff81e60c60-ffffffff81e60de8: intel_pstate_get_cpu_pstates.constprop.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff818711fc)
Location: drivers/cpufreq/intel_pstate.c:1560
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8183a38c)
Location: drivers/cpufreq/intel_pstate.c:1560
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c2aac)
Location: drivers/cpufreq/intel_pstate.c:1560
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff818dee0c)
Location: drivers/cpufreq/intel_pstate.c:1560
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
