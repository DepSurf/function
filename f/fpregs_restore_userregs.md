# Function: <code>fpregs_restore_userregs</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049695)
Location: arch/x86/include/asm/fpu/internal.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104ac80)
Location: arch/x86/include/asm/fpu/internal.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fpregs_restore_userregs();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810530d5)
Location: arch/x86/kernel/fpu/context.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054820)
Location: arch/x86/kernel/fpu/context.h:55
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055570)
Location: arch/x86/kernel/fpu/context.h:55
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
**Symbols:**

```
ffffffff81052fe0-ffffffff810530c1: fpregs_restore_userregs (STB_LOCAL)
ffffffff81054820-ffffffff81054901: fpregs_restore_userregs (STB_LOCAL)
ffffffff81055570-ffffffff81055651: fpregs_restore_userregs (STB_LOCAL)
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
In arch/x86/kernel/fpu/core.c (ffffffff810609b5)
Location: arch/x86/kernel/fpu/context.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062c9a)
Location: arch/x86/kernel/fpu/context.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810638af)
Location: arch/x86/kernel/fpu/context.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
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
In arch/x86/kernel/fpu/core.c (ffffffff810623b5)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064692)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106521b)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
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
In arch/x86/kernel/fpu/core.c (ffffffff81069ec6)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_clone
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bb52)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c881)
Location: arch/x86/kernel/fpu/context.h:54
Inline: True
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
<b>Regular</b>
<ul>
</ul>
