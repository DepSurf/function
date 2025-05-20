# Function: <code>xfeatures_mask_user</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810419c2)
Location: arch/x86/include/asm/fpu/xstate.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810432e8)
Location: arch/x86/include/asm/fpu/xstate.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__init_prepare_fx_sw_frame
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043bd5)
Location: arch/x86/include/asm/fpu/xstate.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041989)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043318)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__init_prepare_fx_sw_frame
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043a79)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81043386)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044c18)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__init_prepare_fx_sw_frame
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810452a6)
Location: arch/x86/include/asm/fpu/xstate.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
