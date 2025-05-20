# Function: <code>copy_fxregs_to_kernel</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d94d)
Location: arch/x86/include/asm/fpu/internal.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039d95)
Location: arch/x86/include/asm/fpu/internal.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__copy
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b266)
Location: arch/x86/include/asm/fpu/internal.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
In arch/x86/kernel/process_64.c (ffffffff8102c9cd)
Location: arch/x86/include/asm/fpu/internal.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039529)
Location: arch/x86/include/asm/fpu/internal.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ab30)
Location: arch/x86/include/asm/fpu/internal.h:191
Inline: True
Inline callers:
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
In arch/x86/kernel/process_64.c (ffffffff8102c861)
Location: arch/x86/include/asm/fpu/internal.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038e6e)
Location: arch/x86/include/asm/fpu/internal.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a3d0)
Location: arch/x86/include/asm/fpu/internal.h:186
Inline: True
Inline callers:
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
In arch/x86/kernel/process_64.c (ffffffff8102ab13)
Location: arch/x86/include/asm/fpu/internal.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81036e92)
Location: arch/x86/include/asm/fpu/internal.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81038260)
Location: arch/x86/include/asm/fpu/internal.h:196
Inline: True
Inline callers:
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
In arch/x86/kernel/process_64.c (ffffffff8102b868)
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103921a)
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a4e8)
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103a712)
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ba24)
Location: arch/x86/include/asm/fpu/internal.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
Location: arch/x86/include/asm/fpu/internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bc12)
Location: arch/x86/include/asm/fpu/internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cf34)
Location: arch/x86/include/asm/fpu/internal.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
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
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e27c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ef8c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ea3c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f60c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810413e1)
Location: arch/x86/include/asm/fpu/internal.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104285c)
Location: arch/x86/include/asm/fpu/internal.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104278c)
Location: arch/x86/include/asm/fpu/internal.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104416c)
Location: arch/x86/include/asm/fpu/internal.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
In arch/x86/kernel/process_64.c (ffffffff8103037a)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebbc)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f78c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e3bc)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102ef8c)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e9fc)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f5cc)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
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
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103fc58)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810408b3)
Location: arch/x86/include/asm/fpu/internal.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
</details>
</li>
</ul>

## Differences
