# Function: <code>__copy_kernel_to_fpregs</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d767)
Location: arch/x86/include/asm/fpu/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039c25)
Location: arch/x86/include/asm/fpu/internal.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102c895)
Location: arch/x86/include/asm/fpu/internal.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039031)
Location: arch/x86/include/asm/fpu/internal.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102c68c)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038b10)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102a851)
Location: arch/x86/include/asm/fpu/internal.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81036b72)
Location: arch/x86/include/asm/fpu/internal.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102b5ad)
Location: arch/x86/include/asm/fpu/internal.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038e42)
Location: arch/x86/include/asm/fpu/internal.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff81074632)
Location: arch/x86/include/asm/fpu/internal.h:431
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
In arch/x86/kernel/process_64.c (ffffffff8102c5cd)
Location: arch/x86/include/asm/fpu/internal.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a522)
Location: arch/x86/include/asm/fpu/internal.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff81077042)
Location: arch/x86/include/asm/fpu/internal.h:431
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
In arch/x86/kernel/process_64.c (ffffffff8102d836)
Location: arch/x86/include/asm/fpu/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b8f2)
Location: arch/x86/include/asm/fpu/internal.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff8107d6d2)
Location: arch/x86/include/asm/fpu/internal.h:434
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
In arch/x86/kernel/fpu/core.c (ffffffff8103df02)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f766)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81080ff5)
Location: arch/x86/include/asm/fpu/internal.h:445
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e6c1)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe96)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810820b5)
Location: arch/x86/include/asm/fpu/internal.h:445
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
In arch/x86/kernel/fpu/core.c (ffffffff8104149c)
Location: arch/x86/include/asm/fpu/internal.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104290c)
Location: arch/x86/include/asm/fpu/internal.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810890c5)
Location: arch/x86/include/asm/fpu/internal.h:449
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
In arch/x86/kernel/fpu/core.c (ffffffff81041a0c)
Location: arch/x86/include/asm/fpu/internal.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104283c)
Location: arch/x86/include/asm/fpu/internal.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810892e5)
Location: arch/x86/include/asm/fpu/internal.h:416
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81043413)
Location: arch/x86/include/asm/fpu/internal.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044223)
Location: arch/x86/include/asm/fpu/internal.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089f40)
Location: arch/x86/include/asm/fpu/internal.h:407
Inline: True
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
**Symbols:**

```
ffffffff81089f40-ffffffff81089f61: __copy_kernel_to_fpregs.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e841)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040016)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810810b5)
Location: arch/x86/include/asm/fpu/internal.h:445
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e041)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f816)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81070005)
Location: arch/x86/include/asm/fpu/internal.h:445
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e681)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe56)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81081065)
Location: arch/x86/include/asm/fpu/internal.h:445
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f831)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810411fa)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81083185)
Location: arch/x86/include/asm/fpu/internal.h:445
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
</ul>

## Differences
