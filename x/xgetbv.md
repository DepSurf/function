# Function: <code>xgetbv</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81082598)
Location: arch/x86/include/asm/fpu/xcr.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
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
In arch/x86/kernel/sev.c (ffffffff81084a68)
Location: arch/x86/include/asm/fpu/xcr.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/kernel/sev.c (ffffffff81093c28)
Location: arch/x86/include/asm/fpu/xcr.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8105511b)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/sev.c (ffffffff810a5d0f)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff820bcc45)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062d09)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/sev.c (ffffffff810bd341)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8213e605)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064701)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/sev.c (ffffffff810c09b6)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff822205f5)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bbc1)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/sev.c (ffffffff810c7e16)
Location: arch/x86/include/asm/fpu/xcr.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
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
