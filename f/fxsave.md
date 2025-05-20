# Function: <code>fxsave</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c987e)
Location: arch/x86/include/asm/fpu/internal.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/core.c (ffffffff810491cd)
Location: arch/x86/include/asm/fpu/internal.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a50c)
Location: arch/x86/include/asm/fpu/internal.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff832aabca)
Location: arch/x86/include/asm/fpu/internal.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/core.c (ffffffff81052e11)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054777)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8345aee4)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/core.c (ffffffff810607a1)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062467)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff83e79f3b)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/core.c (ffffffff81062171)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81063f37)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369c65b)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/core.c (ffffffff81069291)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b447)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff838cc355)
Location: arch/x86/kernel/fpu/legacy.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
