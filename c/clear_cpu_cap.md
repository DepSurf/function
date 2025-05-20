# Function: <code>clear_cpu_cap</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810421c2)
Location: arch/x86/kernel/cpu/cpuid-deps.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff810421f0-ffffffff81042200: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810440a2)
Location: arch/x86/kernel/cpu/cpuid-deps.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff810440d0-ffffffff810440e0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81045aa2)
Location: arch/x86/kernel/cpu/cpuid-deps.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81045ad0-ffffffff81045ae0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810482bf)
Location: arch/x86/kernel/cpu/cpuid-deps.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff810482e0-ffffffff810482f0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048b6f)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81048ba0-ffffffff81048bb0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cc96)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104ccc0-ffffffff8104ccd0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c0f6)
Location: arch/x86/kernel/cpu/cpuid-deps.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104c120-ffffffff8104c130: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dc36)
Location: arch/x86/kernel/cpu/cpuid-deps.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8104dc60-ffffffff8104dc70: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81055406)
Location: arch/x86/kernel/cpu/cpuid-deps.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81055430-ffffffff81055440: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81061349)
Location: arch/x86/kernel/cpu/cpuid-deps.c:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81061370-ffffffff81061388: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fcd9)
Location: arch/x86/kernel/cpu/cpuid-deps.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff8106fd10-ffffffff8106fd28: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810718e5)
Location: arch/x86/kernel/cpu/cpuid-deps.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_spectral_chicken
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81071920-ffffffff81071938: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079105)
Location: arch/x86/kernel/cpu/cpuid-deps.c:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:init_speculation_control
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd_k8
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81079140-ffffffff81079158: clear_cpu_cap (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048cdf)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81048d10-ffffffff81048d20: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8103806f)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff810380a0-ffffffff810380b0: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048b1f)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81048b50-ffffffff81048b60: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049f2f)
Location: arch/x86/kernel/cpu/cpuid-deps.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
  - arch/x86/kernel/cpu/common.c:filter_cpuid_features
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
**Symbols:**

```
ffffffff81049f60-ffffffff81049f70: clear_cpu_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
