# Function: <code>copy_kernel_to_fxregs</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d7bc)
Location: arch/x86/include/asm/fpu/internal.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039c6f)
Location: arch/x86/include/asm/fpu/internal.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/process_64.c (ffffffff8102c991)
Location: arch/x86/include/asm/fpu/internal.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810399f5)
Location: arch/x86/include/asm/fpu/internal.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/process_64.c (ffffffff8102c8bc)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103933f)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/process_64.c (ffffffff8102aafa)
Location: arch/x86/include/asm/fpu/internal.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103727f)
Location: arch/x86/include/asm/fpu/internal.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/process_64.c (ffffffff8102b85b)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103958c)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff81074650)
Location: arch/x86/include/asm/fpu/internal.h:144
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
In arch/x86/kernel/process_64.c (ffffffff8102c872)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aac7)
Location: arch/x86/include/asm/fpu/internal.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff81077060)
Location: arch/x86/include/asm/fpu/internal.h:144
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
In arch/x86/kernel/process_64.c (ffffffff8102dadc)
Location: arch/x86/include/asm/fpu/internal.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bfc7)
Location: arch/x86/include/asm/fpu/internal.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/mm/extable.c (ffffffff8107d6f0)
Location: arch/x86/include/asm/fpu/internal.h:147
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
In arch/x86/kernel/fpu/core.c (ffffffff8103df8d)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f7a0)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81081013)
Location: arch/x86/include/asm/fpu/internal.h:159
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e74c)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fed6)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810820d3)
Location: arch/x86/include/asm/fpu/internal.h:159
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
In arch/x86/kernel/fpu/core.c (ffffffff81041896)
Location: arch/x86/include/asm/fpu/internal.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104291e)
Location: arch/x86/include/asm/fpu/internal.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff810890e3)
Location: arch/x86/include/asm/fpu/internal.h:160
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
In arch/x86/kernel/fpu/core.c (ffffffff81041906)
Location: arch/x86/include/asm/fpu/internal.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104284e)
Location: arch/x86/include/asm/fpu/internal.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089303)
Location: arch/x86/include/asm/fpu/internal.h:160
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
In arch/x86/kernel/fpu/core.c (ffffffff81043306)
Location: arch/x86/include/asm/fpu/internal.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044235)
Location: arch/x86/include/asm/fpu/internal.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/mm/extable.c (ffffffff81089f58)
Location: arch/x86/include/asm/fpu/internal.h:161
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e8cc)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040056)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810810d3)
Location: arch/x86/include/asm/fpu/internal.h:159
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e0cc)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f856)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81070023)
Location: arch/x86/include/asm/fpu/internal.h:159
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e70c)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe96)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff81081083)
Location: arch/x86/include/asm/fpu/internal.h:159
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f8d8)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104123a)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/mm/extable.c (ffffffff810831a3)
Location: arch/x86/include/asm/fpu/internal.h:159
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
</details>
</li>
</ul>

## Differences
