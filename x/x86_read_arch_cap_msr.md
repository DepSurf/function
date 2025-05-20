# Function: <code>x86_read_arch_cap_msr</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810461c0)
Location: arch/x86/kernel/cpu/common.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff810461c0-ffffffff810461d2: x86_read_arch_cap_msr.part.0 (STB_LOCAL)
ffffffff810470c0-ffffffff810470dd: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104af00)
Location: arch/x86/kernel/cpu/common.c:1104
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104af00-ffffffff8104af24: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a3f0)
Location: arch/x86/kernel/cpu/common.c:1122
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104a3f0-ffffffff8104a414: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104bc30)
Location: arch/x86/kernel/cpu/common.c:1123
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104bc30-ffffffff8104bc54: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81052ef0)
Location: arch/x86/kernel/cpu/common.c:1126
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81052ef0-ffffffff81052f14: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105e8b0)
Location: arch/x86/kernel/cpu/common.c:1281
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8105e8b0-ffffffff8105e903: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff83e7bc50)
Location: arch/x86/kernel/cpu/common.c:1304
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
**Symbols:**

```
ffffffff8106cea0-ffffffff8106cef3: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8369e310)
Location: arch/x86/kernel/cpu/common.c:1303
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
**Symbols:**

```
ffffffff8106e850-ffffffff8106e8a3: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff838cdf00)
Location: arch/x86/kernel/cpu/common.c:1328
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_show_state
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:rfds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
**Symbols:**

```
ffffffff81075b40-ffffffff81075b93: x86_read_arch_cap_msr (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046340)
Location: arch/x86/kernel/cpu/common.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81046340-ffffffff81046352: x86_read_arch_cap_msr.part.0 (STB_LOCAL)
ffffffff81047240-ffffffff8104725d: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82894f1c)
Location: arch/x86/kernel/cpu/common.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81036300-ffffffff81036347: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046180)
Location: arch/x86/kernel/cpu/common.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81046180-ffffffff81046192: x86_read_arch_cap_msr.part.0 (STB_LOCAL)
ffffffff81047080-ffffffff8104709d: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 x86_read_arch_cap_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047580)
Location: arch/x86/kernel/cpu/common.c:1098
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81047580-ffffffff81047592: x86_read_arch_cap_msr.part.0 (STB_LOCAL)
ffffffff81048480-ffffffff8104849d: x86_read_arch_cap_msr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
