# Function: <code>pmc_core_lpm_display</code>

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
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c45e0)
Location: drivers/platform/x86/intel_pmc_core.c:654
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff819c45e0-ffffffff819c47e5: pmc_core_lpm_display (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: drivers/platform/x86/intel_pmc_core.c:666
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff819c4940-ffffffff819c4ad6: pmc_core_lpm_display (STB_LOCAL)
ffffffff81c2d466-ffffffff81c2d4b6: pmc_core_lpm_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (0)
Location: drivers/platform/x86/intel_pmc_core.c:832
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff819a9820-ffffffff819a99b7: pmc_core_lpm_display (STB_LOCAL)
ffffffff81c1f6e4-ffffffff81c1f734: pmc_core_lpm_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1132
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff81a56f00-ffffffff81a57097: pmc_core_lpm_display (STB_LOCAL)
ffffffff81d30eee-ffffffff81d30f3e: pmc_core_lpm_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1132
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff81bc66a0-ffffffff81bc6862: pmc_core_lpm_display (STB_LOCAL)
ffffffff81efd304-ffffffff81efd357: pmc_core_lpm_display.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmc_core_lpm_display(struct pmc_dev *pmcdev, struct device *dev, struct seq_file *s, u32 offset, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6e810)
Location: drivers/platform/x86/intel/pmc/core.c:240
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff81d6e810-ffffffff81d6ea23: pmc_core_lpm_display (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmc_core_lpm_display(struct pmc *pmc, struct device *dev, struct seq_file *s, u32 offset, int pmc_index, const char *str, const struct pmc_bit_map **maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddbff0)
Location: drivers/platform/x86/intel/pmc/core.c:254
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show
```
**Symbols:**

```
ffffffff81ddbff0-ffffffff81ddc207: pmc_core_lpm_display (STB_LOCAL)
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
<b>Param added. </b>
<code>int pmc_index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmc_dev *pmcdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>pmcdev, dev, s, offset, str, maps</code> ➡️ <code>pmc, dev, s, offset, pmc_index, str, maps</code>
</li>
</ul>
</details>
</li>
</ul>
