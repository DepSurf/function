# Function: <code>use_xsave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d50d)
Location: arch/x86/include/asm/fpu/internal.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039c25)
Location: arch/x86/include/asm/fpu/internal.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ad04)
Location: arch/x86/include/asm/fpu/internal.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c5bd)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810399c2)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103aca9)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c7ce)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039309)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a549)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a9cd)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81037249)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810383d9)
Location: arch/x86/include/asm/fpu/internal.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b722)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039524)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a659)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81074632)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c742)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa64)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103bb55)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81077042)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d9bc)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bf64)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103d065)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff8107d6d2)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f77e)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103df02)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8e5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
```
```
In arch/x86/mm/extable.c (ffffffff81080ff5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810300de)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e6c1)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040055)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810820b5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810320d0)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041870)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043275)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810890c5)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
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
In arch/x86/kernel/fpu/core.c (ffffffff810418e0)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810432a5)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810892e5)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
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
In arch/x86/kernel/fpu/core.c (ffffffff810432e0)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044bb5)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089f40)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049aaa)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:__restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a296)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aef5)
Location: arch/x86/include/asm/fpu/internal.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff81053896)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81054403)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8345a0c9)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff8106163c)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81062081)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff83e79d1c)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff81062f10)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81063961)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8369c43c)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a1fc)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106ae91)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff838cc11c)
Location: arch/x86/kernel/fpu/internal.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103023e)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e841)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810401d5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810810b5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101fcae)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e041)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f9d5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81070005)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103009e)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e681)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040015)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81081065)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030eee)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f831)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810413e5)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81083185)
Location: arch/x86/include/asm/fpu/internal.h:66
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
</ul>

## Differences
