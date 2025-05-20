# Function: <code>copy_kernel_to_fpregs</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d75b)
Location: arch/x86/include/asm/fpu/internal.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039c19)
Location: arch/x86/include/asm/fpu/internal.h:463
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
In arch/x86/kernel/process_64.c (ffffffff8102c889)
Location: arch/x86/include/asm/fpu/internal.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039025)
Location: arch/x86/include/asm/fpu/internal.h:460
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
In arch/x86/kernel/process_64.c (ffffffff8102c680)
Location: arch/x86/include/asm/fpu/internal.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038b04)
Location: arch/x86/include/asm/fpu/internal.h:455
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
In arch/x86/kernel/process_64.c (ffffffff8102a845)
Location: arch/x86/include/asm/fpu/internal.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81036b66)
Location: arch/x86/include/asm/fpu/internal.h:465
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
In arch/x86/kernel/process_64.c (ffffffff8102b5a1)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038e36)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102c5c1)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a516)
Location: arch/x86/include/asm/fpu/internal.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
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
In arch/x86/kernel/process_64.c (ffffffff8102d82a)
Location: arch/x86/include/asm/fpu/internal.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103b8e6)
Location: arch/x86/include/asm/fpu/internal.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
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
In arch/x86/kernel/fpu/core.c (ffffffff8103def6)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f75a)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e6b5)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe8a)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041480)
Location: arch/x86/include/asm/fpu/internal.h:461
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810428f0)
Location: arch/x86/include/asm/fpu/internal.h:461
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff81041480-ffffffff810414b4: copy_kernel_to_fpregs (STB_LOCAL)
ffffffff810428f0-ffffffff81042924: copy_kernel_to_fpregs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810419f0)
Location: arch/x86/include/asm/fpu/internal.h:428
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042820)
Location: arch/x86/include/asm/fpu/internal.h:428
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff810419f0-ffffffff81041a24: copy_kernel_to_fpregs (STB_LOCAL)
ffffffff81042820-ffffffff81042854: copy_kernel_to_fpregs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
void copy_kernel_to_fpregs(union fpregs_state *fpstate);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810433f0)
Location: arch/x86/include/asm/fpu/internal.h:419
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044200)
Location: arch/x86/include/asm/fpu/internal.h:419
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff810433f0-ffffffff8104342b: copy_kernel_to_fpregs (STB_LOCAL)
ffffffff81044200-ffffffff8104423b: copy_kernel_to_fpregs (STB_LOCAL)
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e835)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104000a)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e035)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f80a)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e675)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fe4a)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f825)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810411ee)
Location: arch/x86/include/asm/fpu/internal.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
