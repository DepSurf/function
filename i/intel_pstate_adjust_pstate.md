# Function: <code>intel_pstate_adjust_pstate</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu, int target_pstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d7d0)
Location: drivers/cpufreq/intel_pstate.c:1720
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid
```
**Symbols:**

```
ffffffff8176d7d0-ffffffff8176d99e: intel_pstate_adjust_pstate (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e2ae6)
Location: drivers/cpufreq/intel_pstate.c:1497
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182bd38)
Location: drivers/cpufreq/intel_pstate.c:1676
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff81857d28)
Location: drivers/cpufreq/intel_pstate.c:1739
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189b0c3)
Location: drivers/cpufreq/intel_pstate.c:1763
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818cd273)
Location: drivers/cpufreq/intel_pstate.c:1809
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0430)
Location: drivers/cpufreq/intel_pstate.c:1817
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff819a0430-ffffffff819a06b9: intel_pstate_adjust_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3190)
Location: drivers/cpufreq/intel_pstate.c:1965
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff819a3190-ffffffff819a33a2: intel_pstate_adjust_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81987c10)
Location: drivers/cpufreq/intel_pstate.c:1962
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81987c10-ffffffff81987e1d: intel_pstate_adjust_pstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2120
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81a319c0-ffffffff81a31bd8: intel_pstate_adjust_pstate (STB_LOCAL)
ffffffff81d2cae7-ffffffff81d2cb0e: intel_pstate_adjust_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2289
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81b9dc80-ffffffff81b9dedc: intel_pstate_adjust_pstate (STB_LOCAL)
ffffffff81ef8e23-ffffffff81ef8e4a: intel_pstate_adjust_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2251
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81d3fad0-ffffffff81d3fd31: intel_pstate_adjust_pstate (STB_LOCAL)
ffffffff820a9274-ffffffff820a929b: intel_pstate_adjust_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2281
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81daa640-ffffffff81daa8a1: intel_pstate_adjust_pstate (STB_LOCAL)
ffffffff8212a67d-ffffffff8212a6a4: intel_pstate_adjust_pstate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pstate_adjust_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2305
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
**Symbols:**

```
ffffffff81e627a0-ffffffff81e629e5: intel_pstate_adjust_pstate (STB_LOCAL)
ffffffff8220c43f-ffffffff8220c466: intel_pstate_adjust_pstate.cold (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff81870e73)
Location: drivers/cpufreq/intel_pstate.c:1809
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff8183beb6)
Location: drivers/cpufreq/intel_pstate.c:1809
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c2723)
Location: drivers/cpufreq/intel_pstate.c:1809
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In drivers/cpufreq/intel_pstate.c (ffffffff818dea33)
Location: drivers/cpufreq/intel_pstate.c:1809
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
