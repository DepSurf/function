# Function: <code>__cpu_invalidate_fpregs_state</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810386f2)
Location: arch/x86/include/asm/fpu/internal.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81036852)
Location: arch/x86/include/asm/fpu/internal.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038c15)
Location: arch/x86/include/asm/fpu/internal.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a3c5)
Location: arch/x86/include/asm/fpu/internal.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ba55)
Location: arch/x86/include/asm/fpu/internal.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dd7b)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e53b)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041922)
Location: arch/x86/include/asm/fpu/internal.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810417fa)
Location: arch/x86/include/asm/fpu/internal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
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
In arch/x86/kernel/fpu/core.c (ffffffff810431fa)
Location: arch/x86/include/asm/fpu/internal.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044678)
Location: arch/x86/include/asm/fpu/internal.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8104956a)
Location: arch/x86/include/asm/fpu/internal.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a997)
Location: arch/x86/include/asm/fpu/internal.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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
In arch/x86/kernel/fpu/core.c (ffffffff81052e89)
Location: arch/x86/kernel/fpu/context.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e73)
Location: arch/x86/kernel/fpu/context.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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
In arch/x86/kernel/fpu/core.c (ffffffff81060828)
Location: arch/x86/kernel/fpu/context.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810629c9)
Location: arch/x86/kernel/fpu/context.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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
In arch/x86/kernel/fpu/core.c (ffffffff81062220)
Location: arch/x86/kernel/fpu/context.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810643df)
Location: arch/x86/kernel/fpu/context.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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
In arch/x86/kernel/fpu/core.c (ffffffff81069340)
Location: arch/x86/kernel/fpu/context.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b8b8)
Location: arch/x86/kernel/fpu/context.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e6bb)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102debb)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4fb)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f692)
Location: arch/x86/include/asm/fpu/internal.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
</details>
</li>
</ul>

## Differences
