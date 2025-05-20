# Function: <code>fpu_state_size_dynamic</code>

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
In arch/x86/kernel/signal.c (ffffffff810424fd)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sigaltstack_size_valid
```
```
In arch/x86/kernel/process.c (ffffffff81050de5)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_release_task_struct
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8105356e)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810549f6)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055fa6)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
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
In arch/x86/kernel/signal.c (ffffffff8104b7ed)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sigaltstack_size_valid
```
```
In arch/x86/kernel/process.c (ffffffff8105e395)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_release_task_struct
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81060fb3)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062556)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063820)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
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
In arch/x86/kernel/signal.c (ffffffff8104c07d)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sigaltstack_size_valid
```
```
In arch/x86/kernel/process.c (ffffffff8105f9d5)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_release_task_struct
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810629b3)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064026)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106579c)
Location: arch/x86/include/asm/fpu/xstate.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
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
In arch/x86/kernel/signal.c (ffffffff810532fd)
Location: arch/x86/include/asm/fpu/xstate.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sigaltstack_size_valid
```
```
In arch/x86/kernel/process.c (ffffffff81066ac5)
Location: arch/x86/include/asm/fpu/xstate.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_release_task_struct
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81069a69)
Location: arch/x86/include/asm/fpu/xstate.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b53e)
Location: arch/x86/include/asm/fpu/xstate.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106cbfc)
Location: arch/x86/include/asm/fpu/xstate.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
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
