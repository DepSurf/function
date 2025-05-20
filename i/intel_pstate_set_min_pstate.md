# Function: <code>intel_pstate_set_min_pstate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_pstate_set_min_pstate(struct cpudata *cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c560)
Location: drivers/cpufreq/intel_pstate.c:1136
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
```
**Symbols:**

```
ffffffff8171c560-ffffffff8171c5f4: intel_pstate_set_min_pstate (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff8174e7c9)
Location: drivers/cpufreq/intel_pstate.c:1595
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
In drivers/cpufreq/intel_pstate.c (ffffffff8176cf4e)
Location: drivers/cpufreq/intel_pstate.c:1531
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
In drivers/cpufreq/intel_pstate.c (ffffffff817e2f11)
Location: drivers/cpufreq/intel_pstate.c:1346
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
In drivers/cpufreq/intel_pstate.c (ffffffff8182b9fb)
Location: drivers/cpufreq/intel_pstate.c:1407
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
In drivers/cpufreq/intel_pstate.c (ffffffff8185797b)
Location: drivers/cpufreq/intel_pstate.c:1470
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
In drivers/cpufreq/intel_pstate.c (ffffffff8189b4f3)
Location: drivers/cpufreq/intel_pstate.c:1501
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
In drivers/cpufreq/intel_pstate.c (ffffffff818cd6a3)
Location: drivers/cpufreq/intel_pstate.c:1547
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff8199f5ec)
Location: drivers/cpufreq/intel_pstate.c:1554
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_cpu_pstates
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
In drivers/cpufreq/intel_pstate.c (ffffffff819a1777)
Location: drivers/cpufreq/intel_pstate.c:1701
Inline: True
Inline callers:
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
In drivers/cpufreq/intel_pstate.c (ffffffff819862a7)
Location: drivers/cpufreq/intel_pstate.c:1701
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
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
In drivers/cpufreq/intel_pstate.c (ffffffff81a308f4)
Location: drivers/cpufreq/intel_pstate.c:1844
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c294)
Location: drivers/cpufreq/intel_pstate.c:2013
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_offline
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
In drivers/cpufreq/intel_pstate.c (ffffffff81d3de14)
Location: drivers/cpufreq/intel_pstate.c:1975
Inline: True
Inline callers:
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
In drivers/cpufreq/intel_pstate.c (ffffffff81da89b4)
Location: drivers/cpufreq/intel_pstate.c:2005
Inline: True
Inline callers:
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
In drivers/cpufreq/intel_pstate.c (ffffffff81e605f4)
Location: drivers/cpufreq/intel_pstate.c:2029
Inline: True
Inline callers:
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
In drivers/cpufreq/intel_pstate.c (ffffffff818712a3)
Location: drivers/cpufreq/intel_pstate.c:1547
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
In drivers/cpufreq/intel_pstate.c (ffffffff8183a433)
Location: drivers/cpufreq/intel_pstate.c:1547
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
In drivers/cpufreq/intel_pstate.c (ffffffff818c2b53)
Location: drivers/cpufreq/intel_pstate.c:1547
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
In drivers/cpufreq/intel_pstate.c (ffffffff818deeb3)
Location: drivers/cpufreq/intel_pstate.c:1547
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
