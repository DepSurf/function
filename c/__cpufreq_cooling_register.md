# Function: <code>__cpufreq_cooling_register</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct thermal_cooling_device *__cpufreq_cooling_register(struct device_node *np, struct cpufreq_policy *policy, u32 capacitance);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (ffff800010adc2d8)
Location: drivers/thermal/cpu_cooling.c:529
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_cooling_register
```
**Symbols:**

```
ffff800010adc2d8-ffff800010adc79c: __cpufreq_cooling_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_cooling_device *__cpufreq_cooling_register(struct device_node *np, struct cpufreq_policy *policy, u32 capacitance);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (c0bbc820)
Location: drivers/thermal/cpu_cooling.c:529
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_cooling_register
```
**Symbols:**

```
c0bbc820-c0bbcd78: __cpufreq_cooling_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_cooling_device *__cpufreq_cooling_register(struct device_node *np, struct cpufreq_policy *policy, u32 capacitance);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/cpu_cooling.c (c000000000bc4650)
Location: drivers/thermal/cpu_cooling.c:529
Inline: False
Direct callers:
  - drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_cooling_register
```
**Symbols:**

```
c000000000bc4650-c000000000bc4cfc: __cpufreq_cooling_register (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
