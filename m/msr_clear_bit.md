# Function: <code>msr_clear_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8141bb70)
Location: arch/x86/lib/msr.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff8141bb70-ffffffff8141bc0b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814640c0)
Location: arch/x86/lib/msr.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff814640c0-ffffffff8146415b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81483360)
Location: arch/x86/lib/msr.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff81483360-ffffffff814833fb: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148caa0)
Location: arch/x86/lib/msr.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff8148caa0-ffffffff8148cb3b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8b80)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff814c8b80-ffffffff814c8c0b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9b10)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff814f9b10-ffffffff814f9b9b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150e3b0)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
```
**Symbols:**

```
ffffffff8150e3b0-ffffffff8150e43b: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153ca20)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff8153ca20-ffffffff8153caab: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d830)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff8155d830-ffffffff8155d8bb: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e72b0)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff815e72b0-ffffffff815e7334: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c4c0)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8160c4c0-ffffffff8160c544: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef760)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff815ef760-ffffffff815ef7e4: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c870)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8165c870-ffffffff8165c8f4: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81775a50)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81775a50-ffffffff81775afd: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a6730)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff818a6730-ffffffff818a67dd: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e95a0)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff818e95a0-ffffffff818e964d: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81930a40)
Location: arch/x86/lib/msr.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81930a40-ffffffff81930aed: msr_clear_bit (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555e20)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff81555e20-ffffffff81555eab: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81546240)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff81546240-ffffffff81546378: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551b60)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff81551b60-ffffffff81551beb: msr_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msr_clear_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b9f0)
Location: arch/x86/lib/msr.c:111
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
  - arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding
```
**Symbols:**

```
ffffffff8156b9f0-ffffffff8156ba7b: msr_clear_bit (STB_GLOBAL)
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
