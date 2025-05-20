# Function: <code>intel_pstate_disable_hwp_interrupt</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c306)
Location: drivers/cpufreq/intel_pstate.c:1663
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
```
**Symbols:**

```
ffffffff81b9b710-ffffffff81b9b777: intel_pstate_disable_hwp_interrupt.part.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d3de86)
Location: drivers/cpufreq/intel_pstate.c:1638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
```
**Symbols:**

```
ffffffff81d3d060-ffffffff81d3d0c7: intel_pstate_disable_hwp_interrupt.part.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff81da8a28)
Location: drivers/cpufreq/intel_pstate.c:1661
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
```
**Symbols:**

```
ffffffff81da7c30-ffffffff81da7c97: intel_pstate_disable_hwp_interrupt.part.0 (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e60668)
Location: drivers/cpufreq/intel_pstate.c:1685
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_suspend
```
**Symbols:**

```
ffffffff81e5f960-ffffffff81e5f9c7: intel_pstate_disable_hwp_interrupt.part.0 (STB_LOCAL)
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
