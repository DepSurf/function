# Function: <code>pmc_core_slps0_display</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3710)
Location: drivers/platform/x86/intel_pmc_core.c:617
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819c3710-ffffffff819c37fb: pmc_core_slps0_display (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: drivers/platform/x86/intel_pmc_core.c:629
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819c3ae0-ffffffff819c3ba0: pmc_core_slps0_display (STB_LOCAL)
ffffffff81c2d402-ffffffff81c2d428: pmc_core_slps0_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: drivers/platform/x86/intel_pmc_core.c:795
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819a8000-ffffffff819a80c0: pmc_core_slps0_display (STB_LOCAL)
ffffffff81c1f680-ffffffff81c1f6a6: pmc_core_slps0_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1095
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81a55330-ffffffff81a553f0: pmc_core_slps0_display (STB_LOCAL)
ffffffff81d30d96-ffffffff81d30dbc: pmc_core_slps0_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1095
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81bc4ac0-ffffffff81bc4b8e: pmc_core_slps0_display (STB_LOCAL)
ffffffff81efd1d6-ffffffff81efd203: pmc_core_slps0_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmc_core_slps0_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6cd20)
Location: drivers/platform/x86/intel/pmc/core.c:203
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81d6cd20-ffffffff81d6ce13: pmc_core_slps0_display (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmc_core_slps0_display(struct pmc *pmc, struct device *dev, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81dda140)
Location: drivers/platform/x86/intel/pmc/core.c:217
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81dda140-ffffffff81dda233: pmc_core_slps0_display (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pmc *pmc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmc_dev *pmcdev</code>
</li>
</ul>
</details>
</li>
</ul>
