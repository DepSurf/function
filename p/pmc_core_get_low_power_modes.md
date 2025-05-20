# Function: <code>pmc_core_get_low_power_modes</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmc_core_get_low_power_modes(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a82a0)
Location: drivers/platform/x86/intel_pmc_core.c:1452
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819a82a0-ffffffff819a8353: pmc_core_get_low_power_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pmc_core_get_low_power_modes(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1782
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81a558b0-ffffffff81a55a67: pmc_core_get_low_power_modes (STB_LOCAL)
ffffffff81d30dbc-ffffffff81d30df3: pmc_core_get_low_power_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pmc_core_get_low_power_modes(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1782
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81bc50b0-ffffffff81bc5299: pmc_core_get_low_power_modes (STB_LOCAL)
ffffffff81efd203-ffffffff81efd225: pmc_core_get_low_power_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pmc_core_get_low_power_modes(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:890
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81d6d110-ffffffff81d6d2fc: pmc_core_get_low_power_modes (STB_LOCAL)
ffffffff820aa04a-ffffffff820aa06c: pmc_core_get_low_power_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pmc_core_get_low_power_modes(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:969
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81dda5d0-ffffffff81dda7b3: pmc_core_get_low_power_modes (STB_LOCAL)
ffffffff8212b53c-ffffffff8212b556: pmc_core_get_low_power_modes.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct platform_device *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmc_dev *pmcdev</code>
</li>
</ul>
</details>
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
</ul>
