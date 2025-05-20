# Function: <code>use_fxsr</code>

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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/fpu/internal.h:74
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/internal.h:74
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/internal.h:74
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/fpu/internal.h:78
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/internal.h:78
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/internal.h:78
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/internal.h:73
Inline: True
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
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
```
```
In arch/x86/mm/extable.c (0)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
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
In arch/x86/kernel/process_64.c (ffffffff8102c87f)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a626)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103bb7c)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff81077060)
Location: arch/x86/include/asm/fpu/internal.h:72
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
In arch/x86/kernel/process_64.c (ffffffff8102dae9)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b9f6)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103d08c)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff8107d6f0)
Location: arch/x86/include/asm/fpu/internal.h:72
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
In arch/x86/kernel/process_64.c (ffffffff8102f8ba)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103df8d)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f90c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff81081013)
Location: arch/x86/include/asm/fpu/internal.h:71
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
In arch/x86/kernel/process_64.c (ffffffff8103021a)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e74c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104007c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff810820d3)
Location: arch/x86/include/asm/fpu/internal.h:71
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
In arch/x86/kernel/process_64.c (ffffffff81032111)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810414ae)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104329e)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810890e3)
Location: arch/x86/include/asm/fpu/internal.h:72
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
In arch/x86/kernel/fpu/core.c (ffffffff810414c2)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810432ce)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089303)
Location: arch/x86/include/asm/fpu/internal.h:72
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
In arch/x86/kernel/fpu/core.c (ffffffff81042ec2)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044bdb)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089f58)
Location: arch/x86/include/asm/fpu/internal.h:72
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
In arch/x86/kernel/fpu/core.c (ffffffff81049a68)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:__restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104af0a)
Location: arch/x86/include/asm/fpu/internal.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/fpu/core.c (ffffffff81053c01)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8345a0d5)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/fpu/core.c (ffffffff810616a1)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff83e79d28)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/fpu/core.c (ffffffff81062f75)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8369c448)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a261)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff838cc128)
Location: arch/x86/kernel/fpu/internal.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/process_64.c (ffffffff8103037a)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e8cc)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810401fc)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff810810d3)
Location: arch/x86/include/asm/fpu/internal.h:71
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
In arch/x86/kernel/process_64.c (ffffffff8101fdfa)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e0cc)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f9fc)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff81070023)
Location: arch/x86/include/asm/fpu/internal.h:71
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
In arch/x86/kernel/process_64.c (ffffffff810301da)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e70c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104003c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff81081083)
Location: arch/x86/include/asm/fpu/internal.h:71
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
In arch/x86/kernel/process_64.c (ffffffff81031043)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f8d8)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104140c)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/mm/extable.c (ffffffff810831a3)
Location: arch/x86/include/asm/fpu/internal.h:71
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
</ul>

## Differences
