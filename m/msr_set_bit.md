# Function: <code>msr_set_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8141bad0)
Location: arch/x86/lib/msr.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8141bad0-ffffffff8141bb69: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81464020)
Location: arch/x86/lib/msr.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff81464020-ffffffff814640b9: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814832c0)
Location: arch/x86/lib/msr.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff814832c0-ffffffff81483359: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148ca00)
Location: arch/x86/lib/msr.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff8148ca00-ffffffff8148ca99: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8af0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff814c8af0-ffffffff814c8b79: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9a80)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff814f9a80-ffffffff814f9b09: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150e320)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8150e320-ffffffff8150e3a9: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c990)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8153c990-ffffffff8153ca19: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d7a0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8155d7a0-ffffffff8155d829: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e7220)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff815e7220-ffffffff815e72a4: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c430)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8160c430-ffffffff8160c4b4: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef6d0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff815ef6d0-ffffffff815ef754: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c7e0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8165c7e0-ffffffff8165c864: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff817759a0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff817759a0-ffffffff81775a43: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a6670)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff818a6670-ffffffff818a6713: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e94e0)
Location: arch/x86/lib/msr.c:102
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff818e94e0-ffffffff818e9583: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81930980)
Location: arch/x86/lib/msr.c:102
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff81930980-ffffffff81930a23: msr_set_bit (STB_GLOBAL)
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
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555d90)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff81555d90-ffffffff81555e19: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81546100)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff81546100-ffffffff81546238: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551ad0)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff81551ad0-ffffffff81551b59: msr_set_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b960)
Location: arch/x86/lib/msr.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
  - arch/x86/kernel/amd_nb.c:__fix_erratum_688
```
**Symbols:**

```
ffffffff8156b960-ffffffff8156b9e9: msr_set_bit (STB_GLOBAL)
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
