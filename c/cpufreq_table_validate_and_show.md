# Function: <code>cpufreq_table_validate_and_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpufreq_table_validate_and_show(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff816b2590)
Location: drivers/cpufreq/freq_table.c:303
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff816b2590-ffffffff816b25b7: cpufreq_table_validate_and_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_table_validate_and_show(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81714990)
Location: drivers/cpufreq/freq_table.c:355
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81714990-ffffffff81714aea: cpufreq_table_validate_and_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_table_validate_and_show(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81746720)
Location: drivers/cpufreq/freq_table.c:355
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81746720-ffffffff8174687a: cpufreq_table_validate_and_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_table_validate_and_show(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81764d30)
Location: drivers/cpufreq/freq_table.c:355
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff81764d30-ffffffff81764ea0: cpufreq_table_validate_and_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_table_validate_and_show(struct cpufreq_policy *policy, struct cpufreq_frequency_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff817dad10)
Location: drivers/cpufreq/freq_table.c:355
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff817dad10-ffffffff817dae80: cpufreq_table_validate_and_show (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
