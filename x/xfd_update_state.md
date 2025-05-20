# Function: <code>xfd_update_state</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81053af2)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810549f6)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055fa6)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
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
In arch/x86/kernel/fpu/core.c (ffffffff8106156a)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062556)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063820)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
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
In arch/x86/kernel/fpu/core.c (ffffffff81062e3a)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064026)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065183)
Location: arch/x86/kernel/fpu/xstate.h:150
Inline: True
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a12a)
Location: arch/x86/kernel/fpu/xstate.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b53e)
Location: arch/x86/kernel/fpu/xstate.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c842)
Location: arch/x86/kernel/fpu/xstate.h:151
Inline: True
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
