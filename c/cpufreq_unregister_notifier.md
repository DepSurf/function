# Function: <code>cpufreq_unregister_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816b0540)
Location: drivers/cpufreq/cpufreq.c:1734
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_exit
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_exit
  - drivers/cpufreq/cpufreq_conservative.c:cs_exit
```
**Symbols:**

```
ffffffff816b0540-ffffffff816b0584: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81711fb0)
Location: drivers/cpufreq/cpufreq.c:1792
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff81711fb0-ffffffff81712064: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817435f0)
Location: drivers/cpufreq/cpufreq.c:1764
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff817435f0-ffffffff817436a4: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761c90)
Location: drivers/cpufreq/cpufreq.c:1767
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff81761c90-ffffffff81761d2f: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d7c70)
Location: drivers/cpufreq/cpufreq.c:1799
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff817d7c70-ffffffff817d7d0f: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818205c0)
Location: drivers/cpufreq/cpufreq.c:1798
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff818205c0-ffffffff8182065f: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c470)
Location: drivers/cpufreq/cpufreq.c:1799
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff8184c470-ffffffff8184c50f: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f4c7)
Location: drivers/cpufreq/cpufreq.c:1949
Inline: True
Direct callers:
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
```
**Symbols:**

```
ffffffff8189242b-ffffffff8189243e: cpufreq_unregister_notifier.cold (STB_LOCAL)
ffffffff8188f480-ffffffff8188f513: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c1700)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff818c1700-ffffffff818c1793: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819932d0)
Location: drivers/cpufreq/cpufreq.c:2000
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff819932d0-ffffffff81993369: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996480)
Location: drivers/cpufreq/cpufreq.c:2016
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff81996480-ffffffff81996519: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197b250)
Location: drivers/cpufreq/cpufreq.c:2022
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff8197b250-ffffffff8197b2e9: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a24180)
Location: drivers/cpufreq/cpufreq.c:2028
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff81a24180-ffffffff81a24219: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8d870)
Location: drivers/cpufreq/cpufreq.c:2060
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81b8d870-ffffffff81b8d91a: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d1c0)
Location: drivers/cpufreq/cpufreq.c:2057
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d2d1c0-ffffffff81d2d26a: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d96430)
Location: drivers/cpufreq/cpufreq.c:2064
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d96430-ffffffff81d964da: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e090)
Location: drivers/cpufreq/cpufreq.c:2105
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81e4e090-ffffffff81e4e13a: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1e158)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
  - drivers/base/arch_topology.c:parsing_done_workfn
```
**Symbols:**

```
ffff800010b1e158-ffff800010b1e22c: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfa0e8)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/base/arch_topology.c:parsing_done_workfn
```
**Symbols:**

```
c0bfa0e8-c0bfa1bc: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c12d70)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
```
**Symbols:**

```
c000000000c12d70-c000000000c12e88: cpufreq_unregister_notifier (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865e20)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff81865e20-ffffffff81865eb3: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182ead0)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff8182ead0-ffffffff8182eb63: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b6bb0)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff818b6bb0-ffffffff818b6c43: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpufreq_unregister_notifier(struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d37a0)
Location: drivers/cpufreq/cpufreq.c:1963
Inline: True
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_exit
```
**Symbols:**

```
ffffffff818d37a0-ffffffff818d3833: cpufreq_unregister_notifier (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
