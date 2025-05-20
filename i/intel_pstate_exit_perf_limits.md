# Function: <code>intel_pstate_exit_perf_limits</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff8171b8b8)
Location: drivers/cpufreq/intel_pstate.c:442
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174db06)
Location: drivers/cpufreq/intel_pstate.c:531
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176c126)
Location: drivers/cpufreq/intel_pstate.c:492
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e1f96)
Location: drivers/cpufreq/intel_pstate.c:433
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182ad04)
Location: drivers/cpufreq/intel_pstate.c:452
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff81856c74)
Location: drivers/cpufreq/intel_pstate.c:468
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189a3c4)
Location: drivers/cpufreq/intel_pstate.c:468
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_exit
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
In drivers/cpufreq/intel_pstate.c (ffffffff818cc813)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff8199f163)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a2f64)
Location: drivers/cpufreq/intel_pstate.c:460
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81987a6a)
Location: drivers/cpufreq/intel_pstate.c:460
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a316a3)
Location: drivers/cpufreq/intel_pstate.c:474
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_pstate_exit_perf_limits(struct cpufreq_policy *policy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c2a1)
Location: drivers/cpufreq/intel_pstate.c:487
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
**Symbols:**

```
ffffffff81b9ba80-ffffffff81b9bace: intel_pstate_exit_perf_limits (STB_LOCAL)
ffffffff81ef8cf4-ffffffff81ef8d09: intel_pstate_exit_perf_limits.cold (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d3f3a8)
Location: drivers/cpufreq/intel_pstate.c:479
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81da9f21)
Location: drivers/cpufreq/intel_pstate.c:492
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e61e20)
Location: drivers/cpufreq/intel_pstate.c:495
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81870413)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff81839993)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c1cc3)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff818ddfd3)
Location: drivers/cpufreq/intel_pstate.c:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_exit
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
