# Function: <code>intel_pstate_adjust_policy_max</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff8176dc03)
Location: drivers/cpufreq/intel_pstate.c:2057
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e3603)
Location: drivers/cpufreq/intel_pstate.c:1820
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c243)
Location: drivers/cpufreq/intel_pstate.c:2011
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff8182b290-ffffffff8182b2d0: intel_pstate_adjust_policy_max.isra.7.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81857200)
Location: drivers/cpufreq/intel_pstate.c:2074
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff81857200-ffffffff81857257: intel_pstate_adjust_policy_max.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a960)
Location: drivers/cpufreq/intel_pstate.c:2100
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff8189a960-ffffffff8189a9b9: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818ccb10)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff818ccb10-ffffffff818ccb70: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a01ee)
Location: drivers/cpufreq/intel_pstate.c:2154
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a3459)
Location: drivers/cpufreq/intel_pstate.c:2305
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81988049)
Location: drivers/cpufreq/intel_pstate.c:2295
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a318d4)
Location: drivers/cpufreq/intel_pstate.c:2467
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81b9db49)
Location: drivers/cpufreq/intel_pstate.c:2633
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d3f649)
Location: drivers/cpufreq/intel_pstate.c:2597
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81daa1b9)
Location: drivers/cpufreq/intel_pstate.c:2623
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e62358)
Location: drivers/cpufreq/intel_pstate.c:2647
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81870710)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff81870710-ffffffff81870770: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839c90)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff81839c90-ffffffff81839cf0: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1fc0)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff818c1fc0-ffffffff818c2020: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de2d0)
Location: drivers/cpufreq/intel_pstate.c:2146
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
**Symbols:**

```
ffffffff818de2d0-ffffffff818de330: intel_pstate_adjust_policy_max.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
