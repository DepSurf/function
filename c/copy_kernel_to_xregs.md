# Function: <code>copy_kernel_to_xregs</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d76c)
Location: arch/x86/include/asm/fpu/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039c2a)
Location: arch/x86/include/asm/fpu/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b0a6)
Location: arch/x86/include/asm/fpu/internal.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8102c89a)
Location: arch/x86/include/asm/fpu/internal.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810399c7)
Location: arch/x86/include/asm/fpu/internal.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a9e4)
Location: arch/x86/include/asm/fpu/internal.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8102c691)
Location: arch/x86/include/asm/fpu/internal.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103930e)
Location: arch/x86/include/asm/fpu/internal.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a297)
Location: arch/x86/include/asm/fpu/internal.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8102a856)
Location: arch/x86/include/asm/fpu/internal.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103724e)
Location: arch/x86/include/asm/fpu/internal.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81038174)
Location: arch/x86/include/asm/fpu/internal.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/process_64.c (ffffffff8102b5b2)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039529)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a3f9)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/mm/extable.c (ffffffff81074637)
Location: arch/x86/include/asm/fpu/internal.h:346
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
In arch/x86/kernel/process_64.c (ffffffff8102c5d2)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa69)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b8f8)
Location: arch/x86/include/asm/fpu/internal.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/mm/extable.c (ffffffff81077047)
Location: arch/x86/include/asm/fpu/internal.h:346
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
In arch/x86/kernel/process_64.c (ffffffff8102d83b)
Location: arch/x86/include/asm/fpu/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bf69)
Location: arch/x86/include/asm/fpu/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ce1a)
Location: arch/x86/include/asm/fpu/internal.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/mm/extable.c (ffffffff8107d6d7)
Location: arch/x86/include/asm/fpu/internal.h:349
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
In arch/x86/kernel/fpu/core.c (ffffffff8103df07)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f551)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81080ffa)
Location: arch/x86/include/asm/fpu/internal.h:338
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e6c6)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fc7c)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810820ba)
Location: arch/x86/include/asm/fpu/internal.h:338
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
In arch/x86/kernel/fpu/core.c (ffffffff81041878)
Location: arch/x86/include/asm/fpu/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042f58)
Location: arch/x86/include/asm/fpu/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810890ca)
Location: arch/x86/include/asm/fpu/internal.h:339
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
In arch/x86/kernel/fpu/core.c (ffffffff810419ce)
Location: arch/x86/include/asm/fpu/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042f12)
Location: arch/x86/include/asm/fpu/internal.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810892ea)
Location: arch/x86/include/asm/fpu/internal.h:339
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
In arch/x86/kernel/fpu/core.c (ffffffff810433ce)
Location: arch/x86/include/asm/fpu/internal.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044851)
Location: arch/x86/include/asm/fpu/internal.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089f45)
Location: arch/x86/include/asm/fpu/internal.h:330
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e846)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fdfc)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810810ba)
Location: arch/x86/include/asm/fpu/internal.h:338
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e046)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f5fc)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff8107000a)
Location: arch/x86/include/asm/fpu/internal.h:338
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e686)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fc3c)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff8108106a)
Location: arch/x86/include/asm/fpu/internal.h:338
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f836)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040fbe)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff8108318a)
Location: arch/x86/include/asm/fpu/internal.h:338
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
</ul>

## Differences
