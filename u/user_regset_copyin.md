# Function: <code>user_regset_copyin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a56d)
Location: include/linux/regset.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a39f)
Location: include/linux/regset.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039c8f)
Location: include/linux/regset.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81037b9f)
Location: include/linux/regset.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039e4f)
Location: include/linux/regset.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ab60)
Location: include/linux/regset.h:282
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff8103ab60-ffffffff8103abfd: user_regset_copyin.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c060)
Location: include/linux/regset.h:282
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff8103c060-ffffffff8103c0fd: user_regset_copyin.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ee61)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103e560-ffffffff8103e5f4: user_regset_copyin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f571)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81042721)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810426f1)
Location: include/linux/regset.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810440d1)
Location: include/linux/regset.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a3c3)
Location: include/linux/regset.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81054566)
Location: include/linux/regset.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81062176)
Location: include/linux/regset.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff81061990-ffffffff81061a3b: user_regset_copyin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81063260)
Location: include/linux/regset.h:253
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff81063260-ffffffff81063312: user_regset_copyin.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a550)
Location: include/linux/regset.h:253
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:ssp_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff8106a550-ffffffff8106a62d: user_regset_copyin.constprop.0 (STB_LOCAL)
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
int user_regset_copyin(unsigned int *pos, unsigned int *count, const void **kbuf, const void **ubuf, void *data, const int start_pos, const int end_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008bc18)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
Direct callers:
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:sve_set
```
**Symbols:**

```
ffff80001008cde0-ffff80001008d000: user_regset_copyin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030c520)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:fpa_set
  - arch/arm/kernel/ptrace.c:gpr_set
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int user_regset_copyin(unsigned int *pos, unsigned int *count, const void **kbuf, const void **ubuf, void *data, const int start_pos, const int end_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000015f1c)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
Direct callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:vsr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:fpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
```
**Symbols:**

```
c000000000013440-c00000000001364c: user_regset_copyin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ptrace.c (ffffffe0000b616e)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_gpr_set
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f6f1)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8102eef1)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f531)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81040811)
Location: include/linux/regset.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
